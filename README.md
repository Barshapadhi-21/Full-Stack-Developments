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
  <p>Cricket began in England during the 16th century as a simple village game. Over time, it spread across the world through British influence and became a major international sport loved in many countries, especially India, England, Australia, Pakistan, South Africa, Sri Lanka, New Zealand, and West Indies.</p>
</div>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
    <img src="https://c.ndtvimg.com/2025-10/51ovgjp_rcb-kohli-de-villiers-and-gayle-bcci_625x300_02_October_25.jpg?im=FeatureCrop,algorithm=dnn,width=1200,height=738" style="width:100%">
  </div>
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTL_FF5IYP0LBXecjF5j_0lBcMQoEaBtl5ZDQ&s" style="width:100%">
  </div>  
  <div class="column">
    <img src="https://images.moneycontrol.com/static-mcnews/2024/03/@ChennaiIPL-1-770x435.jpg?impolicy=website&width=770&height=431" style="width:100%">
  </div>
  <div class="column">
    <img src="https://currentaffairs.adda247.com/wp-content/uploads/multisite/sites/5/2023/08/02144310/all-Indian-cricketer-name.jpg" style="width:100%">
  </div>
</div>

</body>
</html>
