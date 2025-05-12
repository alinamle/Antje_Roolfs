<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Wie hört sich Bayrisch an?</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background: linear-gradient(135deg, #f8f1e4, #f1e7d4);
      font-family: "Segoe UI", sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
    }

    h1 {
      color: #5c4b36;
      margin-bottom: 30px;
      text-align: center;
      font-size: 28px;
    }

    .button {
      background-color: #d4b483;
      color: white;
      padding: 15px 35px;
      border: none;
      border-radius: 10px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: background-color 0.3s ease;
    }

    .button:hover {
      background-color: #c1a26e;
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>
  <h1>Tippe zum Abspielen</h1>
  <button class="button" onclick="document.getElementById('audio').play()">
    ▶ Ton abspielen
  </button>
  <audio id="audio">
    <source src="You See The Trouble With Me.mp3" type="audio/mpeg">
    Dein Browser unterstützt kein Audio.
  </audio>
</body>
</html>
