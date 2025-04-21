<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>NMIクリエイターず ホームページ</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 20px;
    }
    h1 {
      text-align: center;
    }
    .section {
      margin: 30px 0;
    }
    button {
      padding: 10px;
      margin: 5px 0;
      cursor: pointer;
      font-size: 16px;
    }
    .accordion {
      background-color: #eee;
      border: none;
      outline: none;
      width: 100%;
      text-align: left;
    }
    .panel {
      display: none;
      padding-left: 15px;
    }
    .video-link {
      display: flex;
      align-items: center;
      gap: 15px;
      margin: 10px 0;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    .video-link img {
      width: 120px;
      height: auto;
      border-radius: 8px;
    }
    .video-text {
      flex: 1;
    }
    .password-block {
      margin-top: 5px;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .copy-btn {
      padding: 5px 10px;
      font-size: 14px;
      background-color: #ddd;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .link-button {
      display: inline-block;
      margin: 5px 0;
      padding: 10px;
      background-color: #ccc;
      border: none;
      text-decoration: none;
      color: black;
      border-radius: 6px;
    }
    iframe {
      width: 100%;
      height: 315px;
      max-width: 560px;
      border: none;
    }
  </style>
  <script>
    function togglePanel(button) {
      var panel = button.nextElementSibling;
      panel.style.display = panel.style.display === "block" ? "none" : "block";
    }
    function copyPassword(password) {
      navigator.clipboard.writeText(password).then(() => {
        alert("パスワードをコピーしました: " + password);
      }).catch(err => {
        alert("コピーに失敗しました");
      });
    }
  </script>
</head>
<body>

  <h1>NMIクリエイターず ホームページ</h1>

  <!-- 紹介文 -->
  <div class="section" style="display: flex; align-items: center; gap: 20px;">
    <img src="無題90_20250408001231.png" alt="NMIクリエイターずのロゴ" style="width: 200px; height: auto; border-radius: 10px;">
    <div>
      <h2>NMIクリエイターずとは？</h2>
      <p>
        NMIクリエイターずは、動画制作・脚本・映像編集などを手がける高校生クリエイターチームです。<br>
        主な作品には「凱友伝」や「エストリア叙事詩」があり、視聴者にワクワクする世界観を届けることを目指しています。
      </p>
    </div>
  </div>

  <!-- 説明動画 -->
  <div class="section">
    <h2>このサイトの使い方（説明動画）</h2>
    <iframe src="動画のURLをここに入れてください（GitHubにアップロードしたもの）" allowfullscreen></iframe>
  </div>

  <!-- アーカイブ -->
  <div class="section">
    <h2>アーカイブ</h2>
    <button class="accordion" onclick="togglePanel(this)">アーカイブを表示</button>
    <div class="panel">
      <!-- ▼ここからコピーして章を増やせます -->
      <div class="video-link">
  <a href="https://example.com/video-link" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>凱友伝 旧2章</p>
    <div class="password-block">
      <span class="password">GYD_2</span>
      <button class="copy-btn" onclick="copyPassword('GYD_2')">コピー</button>
    </div>
  </div>
</div>
      <div class="video-link">
  <a href="<div class="video-link">
  <a href="https://archivegydoldnitenngo.simdif.com" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>凱友伝 旧2.5章</p>
    <div class="password-block">
      <span class="password">GYD_2.5</span>
      <button class="copy-btn" onclick="copyPassword('GYD_2.5')">コピー</button>
    </div>
  </div>
</div>
    <div class="video-link">
  <a href="<div class="video-link">
  <a href="https://example.com/video-link" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>凱友伝 新1章</p>
    <div class="password-block">
      <span class="password">GYD_n_1</span>
      <button class="copy-btn" onclick="copyPassword('GYD_n_1')">コピー</button>
    </div>
  </div>
</div>
    <div class="video-link">
  <a href="https://example.com/video-link" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>凱友伝 カオストーナメント</p>
    <div class="password-block">
      <span class="password">GYD_chaos</span>
      <button class="copy-btn" onclick="copyPassword('GYD_chaos')">コピー</button>
    </div>
  </div>
</div>
    <div class="video-link">
  <a href="https://example.com/video-link" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>凱友伝 旧3章</p>
    <div class="password-block">
      <span class="password">GYD_3</span>
      <button class="copy-btn" onclick="copyPassword('GYD_3')">コピー</button>
    </div>
  </div>
</div>
    <div class="video-link">
  <a href="https://example.com/video-link" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>凱友伝 新2章</p>
    <div class="password-block">
      <span class="password">GYD_n_2</span>
      <button class="copy-btn" onclick="copyPassword('GYD_n_2')">コピー</button>
    </div>
  </div>
</div>
    <div class="video-link">
  <a href="https://example.com/video-link" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>凱友伝 新3章</p>
    <div class="password-block">
      <span class="password">GYD_n_3</span>
      <button class="copy-btn" onclick="copyPassword('GYD_n_3')">コピー</button>
    </div>
  </div>
</div>
    <div class="video-link">
  <a href="https://example.com/video-link" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>凱友伝 高校生最強ランキング</p>
    <div class="password-block">
      <span class="password">GYD_ranking</span>
      <button class="copy-btn" onclick="copyPassword('GYD_ranking')">コピー</button>
    </div>
  </div>
</div>
    <div class="video-link">
  <a href="https://example.com/video-link" target="_blank">
    <img src="IMG_8540.png" alt="サムネイル">
  </a>
  <div class="video-text">
    <p>未定 乞うご期待</p>
    <div class="password-block">
      <span class="password">ＮＯ password</span>
      <button class="copy-btn" onclick="copyPassword('まだや言うとるやろがい。お前、やりませんねぇｽｷﾞｨ!!')">コピー</button>
    </div>
  </div>
</div>

      <!-- ▲ここまで -->
  </div>
 </div>

  <!-- 各章紹介 -->
  <div class="section">
    <h2>世界観と各章の紹介</h2>
    <button class="accordion" onclick="togglePanel(this)">章紹介を表示</button>
    <div class="panel">
      <!-- ▼ここからコピーして紹介ページを増やせます -->
      <a class="link-button" href="凱友伝紹介ページへのリンク">凱友伝 紹介ページ</a><br>
      <a class="link-button" href="エストリア叙事詩紹介ページへのリンク">エストリア叙事詩 紹介ページ</a><br>
      <!-- ▲ここまで -->
    </div>
  </div>

  <!-- キャラクター紹介 -->
  <div class="section">
    <h2>キャラクター紹介</h2>
    <a class="link-button" href="キャラクター紹介ページへのリンク">キャラクター紹介ページへ</a>
  </div>

  <!-- 用語紹介 -->
  <div class="section">
    <h2>用語紹介</h2>
    <a class="link-button" href="用語紹介ページへのリンク">用語紹介ページへ</a>
  </div>

</body>
</html>
