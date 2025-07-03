<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>3 Iframes com Estilo</title>
  <style>
    body {
      margin: 0;
      padding: 20px;
      font-family: Arial, sans-serif;
      background-color: #f0f0f5;
    }

    .iframe-container {
      display: flex;
      justify-content: space-between;
      gap: 20px;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: 2px solid #333;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .iframe-wrapper {
      flex: 1;
    }

    iframe:hover {
      transform: scale(1.02);
    }
  </style>
</head>
<body>

  <h1>Exemplo com 3 Iframes</h1>

  <div class="iframe-container">
    <div class="iframe-wrapper">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/P273sRlm4tM?si=55JJZk-iBBSPSk1O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
    <div class="iframe-wrapper">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6394.996236075635!2d-43.23290171553422!3d-22.914193729063925!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x997e5bfcef45a7%3A0x3c044ac8f75ca717!2sMaracan%C3%A3%2C%20Rio%20de%20Janeiro%20-%20RJ!5e1!3m2!1spt-BR!2sbr!4v1751562151517!5m2!1spt-BR!2sbr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
    <div class="iframe-wrapper">
      <iframe style="border-radius:12px" src="https://open.spotify.com/embed/album/1WBZyULtlANBKed7Zf9cDP?utm_source=generator" width="100%" height="100%" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
  </div>

</body>
</html>
