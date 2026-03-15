# baseball-definitivo
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="utf-8">
    <title>Baseball Bros - Solo Juego</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <base href="https://cdn.jsdelivr.net/gh/bubbls/UGS-Assets@ae6706e5224c55594c491edfc7f5ad541e2ea02b/baseball%20bros/">
    
    <style>
        body, html { margin: 0; padding: 0; width: 100%; height: 100%; overflow: hidden; background-color: #000; }
        #openfl-content { width: 100%; height: 100%; }
    </style>

    <script type="text/javascript" src="./BaseballBros.js?th=76"></script>
    <script>
        // Bypass de anuncios para que no se bloquee el juego
        function ShowVideo(n) { if(typeof Main !== 'undefined') Main.DoneVideoAd(true); }
        function ShowAd1() {} function ShowAd2() {} function ShowAd3() {}
        function ShowAd4() {} function ShowAd6() {} function ShowAd7() {}
        function ShowAd8() {} function refreshTag() {}
        
        window.addEventListener('keydown', function(e) {
            if ([32, 37, 38, 39, 40].indexOf(e.keyCode) > -1) e.preventDefault();
        }, false);
    </script>
</head>
<body>
    <div id="openfl-content"></div>
    <script type="text/javascript">
        lime.embed("BaseballBros", "openfl-content", 0, 0, { parameters: {} });
    </script>
</body>
</html>
