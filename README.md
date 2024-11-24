<!DOCTYPE html>
<html>
<head>
  <title>BOOK</title>
  <link rel="stylesheet" href="css/style.css" />
  <script src="js/script.js" defer></script>
  <script src="js/clock.js" defer></script>
  <script src="js/lastModified.js" defer></script>
  <script src="js/mouseEvent.js" defer></script>
  <script src="js/screeninfo.js" defer></script>
</head>
<body>
  <div class="book-category sci-fi">
    <h2>科幻小说</h2>
    <div class="book-item">星际穿越 - 评分：4.6</div>
    <div class="book-item high-rating">火星救援 - 评分：4.8</div>
    <div class="book-item" id="special-book">银河帝国 - 评分：4.3</div>
  </div>

  <div class="book-category literature">
    <h2>文学经典</h2>
    <div class="book-item">傲慢与偏见 - 评分：4.4</div>
    <div class="book-item high-rating">了不起的盖茨比 - 评分：4.7</div>
  </div>

  <div class="book-category history">
    <h2>历史</h2>
    <div class="book-item">人类简史 - 评分：4.5</div>
    <div class="book-item">枪炮、病菌与钢铁 - 评分：4.6</div>
  </div>

  
  <!-- 时钟显示 -->
  <div id="clock" style="font-size: 2rem; margin-top: 20px;">时钟加载中...</div>
  
  <!-- 屏幕信息显示 -->
  <div id="screen-info" style="font-size: 1rem; margin-top: 20px;">屏幕信息加载中...</div>
  
  <!-- 鼠标按下坐标显示 -->
  <div id="mouse-coordinates" style="font-size: 1rem; margin-top: 20px;">鼠标坐标加载中...</div>
  
  <!-- 显示网页最后修改时间 -->
  <div id="last-modified" style="font-size: 1rem; margin-top: 20px;">网页最后修改时间加载中...</div>
</body>
</html>
