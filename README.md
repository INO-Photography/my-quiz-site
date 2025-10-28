<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>自己紹介クイズ</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>自己紹介クイズ！</h1>
  <p>私の好きな食べ物は？</p>
  <button onclick="checkAnswer('カレー')">カレー</button>
  <button onclick="checkAnswer('すし')">すし</button>

  <p id="result"></p>

  <script>
    function checkAnswer(answer) {
      if (answer === 'カレー') {
        document.getElementById('result').textContent = '正解！🍛';
      } else {
        document.getElementById('result').textContent = '残念！😢';
      }
    }
  </script>

  <p><a href="index.html">戻る</a></p>
</body>
</html>
