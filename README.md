# 20251113-test3
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>OMORI YUJI OFFICIAL WEBSITE</title>

  <style>
    /* ====== 全体設定 ====== */
    body {
      font-family: "Hiragino Kaku Gothic ProN", "Meiryo", sans-serif;
      margin: 0;
      padding: 0;
      background: #fafafa;
      color: #333;
      line-height: 1.7;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    img {
      display: block;
      max-width: 100%;
      height: auto;
    }

    /* ====== ヘッダー ====== */
    header.header {
      width: 960px;
      height: 170px;
      margin: 0 auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo img {
      height: 60px;
    }

    nav.nav {
      display: flex;
      gap: 20px;
      align-items: center;
    }

    nav.nav a {
      padding: 8px 12px;
      border-radius: 5px;
      transition: background 0.3s;
    }

    nav.nav a:hover {
      background: #ddd;
    }

    /* ====== トップセクション ====== */
    .top {
      text-align: center;
      background: url("down.png") no-repeat center/cover;
      color: #fff;
      padding: 100px 0;
    }

    .top h2 {
      font-size: 2rem;
      margin-bottom: 10px;
    }

    .top p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    /* ====== コンテンツ ====== */
    .content {
      width: 960px;
      margin: 40px auto;
    }

    h3 {
      border-left: 5px solid #555;
      padding-left: 10px;
      margin-top: 40px;
      font-size: 1.4rem;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin-bottom: 10px;
    }

    /* ====== フッター ====== */
    footer {
      text-align: center;
      background: #222;
      color: #fff;
      padding: 30px 0;
      font-size: 0.9rem;
    }

    footer a {
      color: #ffcc00;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>
  <!-- ====== ヘッダー ====== -->
  <header class="header">
    <a href="index.html" class="logo">
      <img src="logo.png" alt="OMORI YUJI LOGO">
    </a>
    <nav class="nav">
      <a href="#about">ABOUT</a>
      <a href="#works">WORKS</a>
      <a href="#contact">CONTACT</a>
    </nav>
  </header>

  <!-- ====== トップセクション ====== -->
  <section class="top">
    <h2>OMORI YUJI OFFICIAL WEBSITE</h2>
    <p>自然と音楽、そして心をつなぐ表現の世界へ</p>
  </section>

  <!-- ====== コンテンツ ====== -->
  <div class="content">
    <h3 id="about">About</h3>
    <p>このウェブサイトは、音楽家・大森祐司の公式サイトです。作品紹介や活動報告、ギャラリーなどを掲載しています。</p>

    <h3 id="works">Works</h3>
    <ul>
      <li>2025年7月から準備を開始し、2026年より本格活動を計画中。</li>
      <li>現在は自然音を中心にしたサウンドデザイン制作を進行。</li>
      <li>その他の活動においては地域イベントや映像作品とのコラボレーションも予定。</li>
    </ul>

    <h3 id="contact">Contact</h3>
    <p>お問い合わせ・ご依頼は <a href="mailto:contact@example.com">contact@example.com</a> までお願いします。</p>
  </div>

  <!-- ====== フッター ====== -->
  <footer>
    <p>© 2025 OMORI YUJI All Rights Reserved.</p>
  </footer>
</body>
</html>

