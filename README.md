# index.html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NMIクリエイターず作品アーカイブ</title>
  <style>
    body {
      font-family: "Helvetica", sans-serif;
      background-color: #f9f9f9;
      text-align: center;
      padding: 50px 20px;
    }

    h1 {
      font-size: 2.2em;
      margin-bottom: 40px;
    }

    .button-container {
      display: flex;
      flex-direction: column;
      gap: 20px;
      max-width: 400px;
      margin: 0 auto;
    }

    .link-button {
      display: block;
      padding: 20px;
      font-size: 1.2em;
      background-color: #444;
      color: white;
      text-decoration: none;
      border-radius: 10px;
      transition: background-color 0.3s;
    }

    .link-button:hover {
      background-color: #666;
    }

    @media (min-width: 600px) {
      .button-container {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
      }
      .link-button {
        width: 180px;
      }
    }
  </style>
</head>
<body>

  <h1>NMIクリエイターず作品アーカイブ</h1>

  <div class="button-container">
    <a href="archive.html" class="link-button">作品アーカイブ</a>
    <a href="blog.html" class="link-button">開発者ブログ</a>
    <a href="setting.html" class="link-button">作品詳細設定</a>
    <a href="event.html" class="link-button">イベントページ</a>
  </div>

</body>
</html>
