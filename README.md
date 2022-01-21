<!DOCTYPE html>
<html>
<head>
<style>
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto auto auto auto;
  grid-gap: 10px;
  background-color: #2196F3;
  padding: 10px;
}

.grid-container > div {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}

.item1 {
  grid-column: 1 / 5;
}
</style>
</head>
<body>

<h1>The grid-column Property</h1>

<p>Use the <em>grid-column</em> property to specify where to place an item.</p>
<p>Item1 will start on column 1 and end before column 5:</p>

<div class="grid-container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>  
  <div class="item4">4</div>
  <div class="item5">5</div>
  <div class="item6">6</div>
  <div class="item7">7</div>
  <div class="item8">8</div>  
  <div class="item9">9</div>
  <div class="item10">10</div>
  <div class="item11">11</div>
  <div class="item12">12</div>
  <div class="item13">13</div>
  <div class="item14">14</div>
  <div class="item15">15</div>
</div>

</body>
</html>

<link href="https://github.com/emreduman3000/emreduman3000/blob/main/index.html?raw=true" rel="import" />

<html>
  <body>
    <div class="externalHtmlIntoADiv">

    </div>
  </body>
</html>

<script type="text/javascript">
  $(function ()
  {
    $(".externalHtmlIntoADiv").load("index.html"));
  });
</script>




<hr>
<br>
<img src="https://github.com/emreduman3000/emreduman3000/blob/main/emre.jpg?raw=true" width="300" height="400">
<h1 align="center">Hi, I'm EMRE DUMAN </h1>
