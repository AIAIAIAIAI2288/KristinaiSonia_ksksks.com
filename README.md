# KristinaiSonia_ksksks.com
Bonia
<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Страница с видео</title>
    <style>
      body {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
        background-color: #f0f2f5;
        color: #333;
        display: flex;
        justify-content: center;
        min-height: 100vh;
      }
      .page-wrapper {
        max-width: 900px;
        width: 100%;
        padding: 20px;
      }
      h1 {
        text-align: center;
        margin-bottom: 12px;
        font-size: 28px;
      }
      p.description {
        text-align: center;
        max-width: 700px;
        margin: 0 auto 32px;
        line-height: 1.5;
        color: #555;
      }
      .video-container {
        position: relative;
        padding-bottom: 56.25%; /* соотношение сторон 16:9 */
        padding-top: 0;
        height: 0;
        overflow: hidden;
        border-radius: 12px;
        box-shadow: 0 8px 24px rgba(0,0,0,0.12);
        background: #000;
      }
      .video-container iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: 0;
      }
      @media (max-width: 600px) {
        h1 { font-size: 24px; }
        .page-wrapper { padding: 12px; }
      }
    </style>
  </head>
  <body>
    <div class="page-wrapper">
      <h1>Видео на странице</h1>
      <p class="description">
        Для Кристины и Сонтика
      </p>
      <div class="video-container">
        <iframe
          src="https://www.youtube-nocookie.com/embed/-KVWtTYrIc0"
          title="Видео"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
          allowfullscreen
        ></iframe>
      </div>
    </div>
  </body>
</html>
