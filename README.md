<!DOCTYPE html>
<html>
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

.header {
  text-align: center;
  padding: 32px;
}

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    -ms-flex: 50%;
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    -ms-flex: 100%;
    flex: 100%;
    max-width: 100%;
  }
}
</style>
<body>

<!-- Header -->
<div class="header">
  <h1>Responsive Image Grid</h1>
  <p>A red rose is one of the most well-known flowers in the world. It is admired for its bright red color, smooth petals, and pleasant fragrance. Red roses are often seen in gardens, bouquets, and decorative arrangements. Apart from beauty, a red rose carries symbolic meaning. It commonly represents respect, admiration, and appreciation. In culture and history, red roses have been used as symbols in poetry, art, and celebrations. They are also given during special occasions to express positive feelings and kindness.</p>
</div>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
    <img src="https://www.flowersinthewoods.com.au/cdn/shop/products/image_c5186ebc-d195-4cf3-82e2-6e1aa8b1996e_1024x1024.jpg?v=1686096217" style="width:100%">
  </div>
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcThW4LI_igYP4QkCXFatNi_KJGoQtBL5HHk2g&s" style="width:100%">
  </div>  
  <div class="column">
    <img src="https://media.istockphoto.com/id/510803688/photo/dozen-red-roses-proposal-selective-focus.jpg?s=612x612&w=0&k=20&c=AkfALzEIAxrw7Yuyku0-luEqpNopNgzyio-WSOb-vY4=" style="width:100%">
  </div>
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRotcjsMXWsC6mmVTVpbgPja72Ge6Dc7tUHyQ&s" style="width:100%">
  </div>
</div>

</body>
</html>
