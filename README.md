<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>NMIクリエイターずホームページ</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 20px;
    }
    h1 {
      text-align: center;
    }
    .intro {
      display: flex;
      align-items: center;
      margin-bottom: 40px;
    }
    .intro img {
      max-width: 150px;
      margin-right: 20px;
    }
    .video {
      margin-bottom: 40px;
    }
    .accordion {
      margin-bottom: 20px;
    }
    details {
      margin-bottom: 10px;
      background: #fff;
      border: 1px solid #ccc;
      border-radius: 5px;
      padding: 10px;
    }
    summary {
      font-weight: bold;
      cursor: pointer;
    }
    .video-entry {
      display: flex;
      align-items: center;
      border: 1px solid #ccc;
      border-radius: 5px;
      padding: 10px;
      margin-bottom: 10px;
      background-color: #fff;
    }
    .video-entry img {
      max-width: 100px;
      margin-right: 15px;
      cursor: pointer;
    }
    .video-info {
      flex: 1;
    }
    .copy-button {
      margin-top: 5px;
    }
    .link-button {
      display: inline-block;
      background-color: #eee;
      padding: 10px 15px;
      margin: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
      text-decoration: none;
      color: #000;
    }
    .link-button:hover {
      background-color: #ddd;
    }
  </style>
  <script>
    function copyPassword(password) {
      navigator.clipboard.writeText(password);
      alert("パスワードをコピーしました: " + password);
    }
  </script>
</head>
<body>

  <h1>NMIクリエイターずホームページ</h1>

  <div class="intro">
    <img src="無題90_20250408001231.png" alt="NMIクリエイターず ロゴ" />
    <p>
      NMIクリエイターずは、動画制作・脚本・映像編集などを手がける高校生クリエイターチームです。<br>
      主な作品には「凱友伝」や「エストリア叙事詩」があり、視聴者にワクワクする世界観を届けることを目指しています。
    </p>
  </div>

  <div class="video">
    <h2>ホームページの使い方（解説動画）</h2>
    <video width="100%" controls>
      <source src="ファイル名" type="video/mp4">
      お使いのブラウザは動画に対応していません。
    </video>
  </div>

  <div class="accordion">
    <details>
      <summary>アーカイブページ</summary>
      <details>
        <summary>凱友伝</summary>
        <div class="video-entry">
          <a href="https://archivegydoldni.simdif.com"><img src="IMG_8540.png" alt="旧2章" /></a>
          <div class="video-info">
            <div>凱友伝 旧2章</div>
            <button class="copy-button" onclick="copyPassword('GYD_2')">パスワードをコピー</button>
          </div>
        </div>
        <div class="video-entry">
          <a href="https://archivegydoldnitenngo.simdif.com"><img src="IMG_8543.png" alt="旧2.5章" /></a>
          <div class="video-info">
            <div>凱友伝 旧2.5章</div>
            <button class="copy-button" onclick="copyPassword('GYD_2.5')">パスワードをコピー</button>
          </div>
        </div>
        <div class="video-entry">
          <a href="https://gydnewchapterone.simdif.com"><img src="IMG_8540.png" alt="新1章" /></a>
          <div class="video-info">
            <div>凱友伝 新1章</div>
            <button class="copy-button" onclick="copyPassword('GYD_n_1')">パスワードをコピー</button>
          </div>
        </div>
        <div class="video-entry">
          <a href="ここにURL"><img src="IMG_8540.png" alt="カオストーナメント" /></a>
          <div class="video-info">
            <div>凱友伝 カオストーナメント</div>
            <button class="copy-button" onclick="copyPassword('GYD_chaos')">パスワードをコピー</button>
          </div>
        </div>
        <div class="video-entry">
          <a href="ここにURL"><img src="IMG_8543.png" alt="旧3章" /></a>
          <div class="video-info">
            <div>凱友伝 旧3章</div>
            <button class="copy-button" onclick="copyPassword('GYD_3')">パスワードをコピー</button>
          </div>
        </div>
        <div class="video-entry">
          <a href="ここにURL"><img src="IMG_8540.png" alt="新2章" /></a>
          <div class="video-info">
            <div>凱友伝 新2章</div>
            <button class="copy-button" onclick="copyPassword('GYD_n_2')">パスワードをコピー</button>
          </div>
        </div>
        <div class="video-entry">
          <a href="ここにURL"><img src="IMG_8540.png" alt="新3章" /></a>
          <div class="video-info">
            <div>凱友伝 新3章</div>
            <button class="copy-button" onclick="copyPassword('GYD_n_3')">パスワードをコピー</button>
          </div>
        </div>
        <div class="video-entry">
          <a href="ここにURL"><img src="IMG_8540.png" alt="高校生最強ランキング" /></a>
          <div class="video-info">
            <div>凱友伝 高校生最強ランキング</div>
            <button class="copy-button" onclick="copyPassword('GYD_ranking')">パスワードをコピー</button>
          </div>
        </div>
      </details>
      <details>
        <summary>エストリア叙事詩</summary>
        <div class="video-entry">
          <img src="IMG_8544.jpeg" alt="エストリア叙事詩" />
          <div class="video-info">
            <div>近日公開！<br>乞うご期待！</div>
          </div>
        </div>
      </details>
    </details>
  </div>

  <div class="accordion">
    <details>
      <summary>世界観や各章紹介(準備中､､､)</summary>
      <a class="link-button" href="ここにURL">凱友伝</a>
      <a class="link-button" href="ここにURL">エストリア叙事詩</a>
    </details>
  </div>

  <a class="link-button" href="ここにURL">用語辞典(準備中)</a>
  <a class="link-button" href="ここにURL">キャラクター紹介(準備中)</a>

</body>
</html>
