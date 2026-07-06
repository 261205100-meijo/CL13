# CL13
<!DOCTYPE html>
<html lang="ja">
    <head>
        <meta charset="UTF-8">
        <title>CL103</title>
        <script type="text/javascript">
            function PrintMessage()
            {
                var textBox = document.getElementById("answer");
                var msg = textBox.value + "正解は6匹です！5匹じゃないぞー";
                textBox.value = msg;
            }
        </script>
    </head>
    <body style="margin: 0%; padding: 0%;">
        <img src="bg0.png" width="100%" height="100%">
        <img src="butterfly.gif" style="position: absolute; top: 20px; left: 20px;">
        <img src="butterfly.gif" style="position: absolute; top: 100px; left: 500px;">
        <img src="butterfly.gif" style="position: absolute; top: 400px; left: 200px;">
        <img src="butterfly.gif" style="position: absolute; top: 400px; left: 1400px;">
        <img src="butterfly.gif" style="position: absolute; top: 700px; left: 1000px;">
        <img src="butterfly.gif" style="position: absolute; top: 750px; left: 500px; width: 25px; height: 25px;">
        <div style="margin: 50px; padding: 50px; border: 1px solid #333333;">
            <h1>Q.蝶々の数は何匹でしょう？</h1>
            <h2>
                <input type="button" value="ここをクリック(^▽^)/" onclick="PrintMessage()">
                <textarea id="answer" cols="30" rows="1"></textarea>
            </h2>
        </div>
    </body>
</html>
