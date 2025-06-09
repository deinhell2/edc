<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bu Sefer Gerçekten</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to top, #ffe5e5, #ffc1c1);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      text-align: center;
      color: #4a0000;
      padding: 20px;
    }

    h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.2rem;
      max-width: 500px;
      margin: 10px 0;
    }

    .heart {
      font-size: 3rem;
      animation: pulse 1.2s infinite;
      margin: 15px 0;
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    .button {
      background-color: #d40057;
      color: white;
      padding: 12px 25px;
      font-size: 1rem;
      border: none;
      border-radius: 30px;
      margin-top: 25px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .button:hover {
      background-color: #ff4d8a;
    }

    .message {
      display: none;
      margin-top: 20px;
      font-size: 1.3rem;
      color: #990000;
    }

    .music {
      margin-top: 40px;
      max-width: 90%;
    }

    iframe {
      border-radius: 12px;
    }
  </style>
</head>
<body>

  <h1>Bu Sefer Gerçekten...</h1>
  <div class="heart">❤️</div>
  <p>Sana karşı hatalar yaptım, belki kırıldın, uzaklaştın...</p>
  <p>Ama inan, kalbim hâlâ seninle. Değişmeye hazırım.</p>
  <p>İlgisiz olmayacağım. Üzerine düşeceğim. Sevgini hak edeceğim.</p>

  <button class="button" onclick="showMessage()">Bana Bir Şans Daha Ver 💌</button>

  <div class="message" id="response">
    Söz veriyorum: Bu sefer sadece sevmeye değil, göstermeye de geldim.
  </div>

  <div class="music">
    <iframe width="300" height="170"
      src="https://www.youtube.com/embed/SA7AIQw-7Ms?autoplay=1&loop=1&playlist=SA7AIQw-7Ms"
      title="Him & I"
      frameborder="0"
      allow="autoplay; encrypted-media"
      allowfullscreen>
    </iframe>
  </div>

  <script>
    function showMessage() {
      document.getElementById("response").style.display = "block";
    }
  </script>

</body>
</html>
