# index
 	
<html lang="ja">
 <head>
  <meta charset="utf-8" />
	 
<style type="text/css">

  p {
color: #fffafa;
font-size: 1.5em;
 }
<!--
 .red {color:#ff0000;}
 .grey {color:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}
 -->
	
.date:before{content:"20181115";}
	
	
 #preview{
	position: relative;
	border: 3px solid #333;
	background: #444;
	padding: 5px;
	display: none;
	color: #FFF;
	text-align: center;
}

main {
background-color: rgba(255, 255, 255, 0.3);
}

section {
background-color: rgba(0, 225, 0, 0.5);
}

</style>

<script>
    <!-- SpreadJSのカルチャに「ja-jp（日本語）」を指定 -->
    <meta name="spreadjs culture" content="ja-jp">

    <!-- SpreadJSの全機能ライブラリをロード -->
    <script src="http://localhost/spreadjs/9201610/scripts/gc.spread.sheets.all.9.20161.0.min.js">

    <!-- SpreadJSの日本語リソースをロード -->
    <script src="http://localhost/spreadjs/9201610/scripts/resources/ja/gc.spread.sheets.resources.ja.9.20161.0.min.js">

    </script>

      </head>
  <body>
     window.onload = function() {
        var spread = new GC.Spread.She
ets.Workbook(document.getElementById("ss"));
        var sheet = spread.getActiveSheet();
      };   
      <!-- スプレッドシートに「Excel 2016 カラフル」テーマを指定 -->
    <link  href="http://localhost/spreadjs/9201610/css/gc.spread.sheets.excel2016colorful.9.20161.0.css" rel="stylesheet">
    
    <!-- スプレッドシートが表示される場所 -->
    <div id="ss" style="width:555px; height:200px;"></div>
    
    <a href="https://www.buildinsider.net/pr/grapecity/spreadjs/01" target="_blank">エクセルライクなグリッド</a>
    
  </body>
</html>
