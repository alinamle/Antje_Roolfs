<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Ton abspielen</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background: linear-gradient(135deg, #f0f4f8, #d9e2ec);
      font-family: "Segoe UI", sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
    }

    h1 {
      color: #102a43;
      margin-bottom: 20px;
      text-align: center;
    }

    .button {
      background-color: #2f80ed;
      color: white;
      padding: 15px 30px;
      border: none;
      border-radius: 10px;
      font-size: 18px;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: background-color 0.3s ease;
    }

    .button:hover {
      background-color: #1c60b3;
    }

    footer {
      margin-top: 50px;
      font-size: 14px;
      color: #627d98;
    }
  </style>
</head>
<body>
  <h1>Tippe auf den Button, um den Ton zu hören</h1>
  <button class="button" onclick="document.getElementById('audio').play()">
    ▶ Ton abspielen
  </button>
  <audio id="audio">
    <source src="You See The Trouble With Me.mp3" type="audio/mpeg">
    Dein Browser unterstützt kein Audio.
  </audio>

  <footer>© Dein Projektname</footer>
</body>
</html>
