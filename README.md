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
  <p>은 RM, 진, 슈가, 제이홉, 지민, 뷔, 정국으로 이루어진 한국의 세계적인 보이 그룹이다. 이들은 청소년과 자아 사랑, 감정, 현실적인 고민 등을 음악으로 표현하여 전 세계 팬들과 깊게 소통하고 있다. BTS는 빌보드 차트, 그래미 노미네이션, 기네스 기록, UN 연설 등 다양한 글로벌 성과를 이루며 K-POP을 국제적으로 더욱 알렸다.
 </p>
</div>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
    <img src="https://assets.vogue.in/photos/64003791f02f494b19853b16/master/w_1600%2Cc_limit/1389408711">
  </div>
  <div class="column">
    <img src="https://ztvcj4n2fh.execute-api.ap-south-1.amazonaws.com/Prod/times-special/Bombaytimes/posts/1763557077877/assets/images/1763557856906-suga.jpg">
  </div>  
  <div class="column">
    <img src="https://i.zoomtventertainment.com/story/jin.png" style="width:100%">
  </div>
  <div class="column">
    <img src="https://filmfare.wwmindia.com/content/2025/may/btsrmbtsrm1748350663.jpg" style="width:100%">
  </div>
  <div class="column">
    <img src="https://m.media-amazon.com/images/I/41IzrEh5tHL._AC_UF894,1000_QL80_.jpg" style="width:100%">
  </div>
   <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqP0Y_W6vvoiMM1pA4uenVL9zoSRXZwlJTeQ&s" style="width:100%">
  </div>
  <div class="column">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTir0F1ixGbrJ_7tNVv0n6SvS__5yLFXs7FRQ&s" style="width:100%">
  </div>
  <div class="column">
    <img src="https://hips.hearstapps.com/hmg-prod/images/jimin-jungkook-rm-j-hope-v-jin-and-suga-of-the-k-pop-boy-news-photo-1765824739.pjpeg?crop=1xw:0.7922xh;0,0.0135xh" style="width:100%">
  </div>
</div>

</body>
</html>
