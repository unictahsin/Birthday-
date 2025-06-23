<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday, Maimona</title>
  <style>
    body {
      font-family: Arial;
      background-color: #fff0f5;
      text-align: center;
      padding: 50px;
    }
    button {
      background-color: #ff69b4;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 18px;
      border-radius: 10px;
      cursor: pointer;
    }
    .message {
      margin-top: 30px;
      font-size: 20px;
      color: #d6336c;
      display: none;
    }
  </style>
</head>
<body>
  <h1>🌸 Happy Birthday, Maimona 🌸</h1>
  <p>Click the button below to see your special message 💖</p>
  <button onclick="showMessage()">🎁 শুভেচ্ছা দেখাও</button>

  <div class="message" id="bdayMsg">
    <p>Wishing you quiet peace, gentle joy,<br>
    and a future that blooms with grace.<br>
    Even from afar, I’m silently hoping<br>
    your heart stays light and your smile lasts long. 🤍<br><br>
    — Tahsin ❤️‍🩹</p>
  </div>

  <script>
    function showMessage() {
      document.getElementById("bdayMsg").style.display = "block";
    }
  </script>
</body>
</html>
