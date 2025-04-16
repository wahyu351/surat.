# Surat untuk kamu
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Surat Cinta untuk Risma</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffe6e6;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    h1 {
      margin-top: 40px;
      font-size: 24px;
      color: #ff4d4d;
    }
    .envelope {
      width: 200px;
      height: 150px;
      margin: 40px auto 20px;
      background: #ff4d4d;
      position: relative;
      border-radius: 10px;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .envelope:hover {
      transform: scale(1.05);
    }
    .flap {
      width: 0;
      height: 0;
      border-left: 100px solid transparent;
      border-right: 100px solid transparent;
      border-bottom: 75px solid #ff9999;
      position: absolute;
      top: -75px;
      left: 0;
    }
    #message {
      display: none;
      margin-top: 20px;
    }
    #message img {
      width: 150px;
    }
  </style>
</head>
<body>

  <h1>Klik amplop ini 💌</h1>

  <div class="envelope" onclick="openEnvelope()">
    <div class="flap"></div>
  </div>

  <div id="message">
    <img src="93f881ab984a7178916e8d8d8413152c.jpg" alt="Love" />
    <h2>Untuk Risma Winda Sari 💌</h2>
  </div>

  <script>
    function openEnvelope() {
      document.querySelector(".envelope").style.display = "none";
      document.querySelector("h1").style.display = "none";
      document.getElementById("message").style.display = "block";
    }
  </script>

</body>
</html>
