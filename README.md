# index
 	
<!DOCTYPE html>
<html>
  <head>

    <!-- SpreadJSのカルチャに「ja-jp（日本語）」を指定 -->
    <meta name="spreadjs culture" content="ja-jp">

    <!-- スプレッドシートに「Excel 2016 カラフル」テーマを指定 -->
    <link  href="http://localhost/spreadjs/9201610/css/gc.spread.sheets.excel2016colorful.9.20161.0.css" rel="stylesheet">

    <!-- SpreadJSの全機能ライブラリをロード -->
    <script src="http://localhost/spreadjs/9201610/scripts/gc.spread.sheets.all.9.20161.0.min.js"></script>

    <!-- SpreadJSの日本語リソースをロード -->
    <script src="http://localhost/spreadjs/9201610/scripts/resources/ja/gc.spread.sheets.resources.ja.9.20161.0.min.js"></script>

    <script>
      window.onload = function() {

        // スプレッドシートを生成する処理
        var spread = new GC.Spread.Sheets.Workbook(document.getElementById("ss"));
        var sheet = spread.getActiveSheet();
        // ……ここでさまざまな処理を実行できる……

      };
    </script>
  </head>
  <body>
    
    <!-- スプレッドシートが表示される場所 -->
    <div id="ss" style="width:555px; height:200px;"></div>
    
  </body>
</html>
