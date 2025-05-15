# nxt2

<!DOCTYPE html>
<html lang="nl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NXT Freerunning</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      overflow-x: hidden;
      font-family: sans-serif;
      color: white;
      background-color: black;
    }

    .video-background {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      overflow: hidden;
      z-index: -1;
    }

    .video-background iframe {
      width: 100vw;
      height: 56.25vw;
      min-height: 100vh;
      min-width: 177.77vh;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      pointer-events: none;
    }

    .content {
      position: relative;
      z-index: 1;
      padding: 100px 20px 40px;
      text-align: center;
      background: rgba(0,0,0,0.6);
    }

    h1 {
      font-size: 4em;
      color: #00ff88;
      text-shadow: 0 0 10px #00ff88;
    }

    .section {
      padding: 60px 20px;
      text-align: center;
    }

    .link-box {
      background: rgba(255, 255, 255, 0.9);
      color: #111;
      max-width: 500px;
      margin: 40px auto;
      padding: 20px;
      border-radius: 10px;
      font-weight: bold;
      word-wrap: break-word;
    }

    .link-box input {
      width: 100%;
      padding: 10px;
      font-size: 1em;
      border: none;
      border-radius: 5px;
      margin-top: 10px;
    }

    footer {
      background: rgba(0,0,0,0.7);
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

<div class="video-background">
  <iframe src="https://www.youtube.com/embed/Oyu8Cif6L5A?autoplay=1&mute=1&controls=0&loop=1&playlist=Oyu8Cif6L5A&modestbranding=1&showinfo=0&rel=0"
          frameborder="0"
          allow="autoplay; fullscreen"
          allowfullscreen>
  </iframe>
</div>

<div class="content">
  <h1>NXT Freerunning</h1>
  <p>Pure stijl. Pure kracht. Pure vrijheid.</p>
</div>

<section class="section">
  <h2>🔗 Deel onze website</h2>
  <div class="link-box">
    <p>Copy & share:</p>
    <input type="text" value="https://jouwgithubsite.github.io/nxt-freerunning" readonly onclick="this.select()">
  </div>
</section>

<footer>
  &copy; 2025 NXT Freerunning | Insta: @nxtfreerunning
</footer>

</body>
</html>
