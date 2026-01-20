<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CHG Lite Whitepaper</title>
  <meta name="description" content="CHGはSolanaベースの実験的トークンプロジェクト。透明性とシンプルさを重視したライトホワイトペーパー。">

  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
        "Hiragino Kaku Gothic ProN", Meiryo, sans-serif;
      line-height: 1.8;
      color: #222;
      background: #fafafa;
    }

    header {
      background: linear-gradient(135deg, #0d6efd, #6610f2);
      color: #fff;
      padding: 56px 16px;
      text-align: center;
    }

    header h1 {
      font-size: 2rem;
      margin-bottom: 8px;
    }

    header p {
      font-size: 1rem;
      opacity: 0.9;
    }

    main {
      max-width: 800px;
      margin: 0 auto;
      padding: 40px 16px;
      background: #fff;
    }

    h2 {
      margin-top: 40px;
      font-size: 1.5rem;
      border-bottom: 2px solid #eee;
      padding-bottom: 8px;
    }

    p {
      margin-top: 16px;
      font-size: 1rem;
    }

    ul {
      margin-top: 16px;
      padding-left: 20px;
    }

    li {
      margin-bottom: 8px;
    }

    .info-box {
      background: #f4f6f8;
      padding: 16px;
      border-radius: 6px;
      margin-top: 16px;
    }

    .token-ca {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #e8f0fe;
      padding: 12px 16px;
      border-radius: 6px;
      margin-top: 8px;
    }

    .token-ca button {
      padding: 6px 12px;
      border: none;
      background: #0d6efd;
      color: #fff;
      border-radius: 4px;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 24px;
      font-size: 0.9rem;
      color: #666;
    }

    a {
      color: #0d6efd;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<header>
  <h1>CHG Lite Whitepaper</h1>
  <p>Solana-based Experimental Token Project</p>
</header>

<main>
  <h2>プロジェクト概要</h2>
  <p>CHG は、シンプルさと透明性、コミュニティ主導の開発に重点を置いた実験的な Solana ベースのトークンプロジェクトです。</p>
  <p>本プロジェクトは現在、初期のコンセプト段階にあり、Solana ブロックチェーン上におけるトークン化されたユーティリティの技術的・概念的検証を目的としています。</p>

  <h2>課題</h2>
  <p>多くの暗号資産プロジェクトは、過度な複雑さ、透明性の欠如、現実世界での有用性の不明確さという課題を抱えています。</p>

  <h2>解決策</h2>
  <p>CHG は、以下を目的とした最小限かつ透明性の高いフレームワークを提供します。</p>
  <ul>
    <li>トークンベースのインタラクション検証</li>
    <li>コミュニティ参加モデルの実験</li>
    <li>将来的な Web3 統合に向けた基盤構築</li>
  </ul>

  <h2>トークン情報</h2>
  <div class="info-box">
    <ul>
      <li><strong>Blockchain:</strong> Solana</li>
      <li><strong>Token Standard:</strong> SPL Token</li>
      <li><strong>Status:</strong> Test / Concept Stage</li>
    </ul>
    <div class="token-ca">
      <code id="ca">6c6Qh4aXeTwNZ7jZsXSoNreujVgxiszV3MK4UR3xpump</code>
      <button onclick="copyCA()">Copy CA</button>
    </div>
  </div>

  <h2>ロードマップ</h2>
  <ul>
    <li>フェーズ1: コンセプト設計・テスト</li>
    <li>フェーズ2: トークン展開（Devnet → Mainnet）</li>
    <li>フェーズ3: ユーティリティ実験</li>
    <li>フェーズ4: 一般公開</li>
  </ul>

  <h2>免責事項</h2>
  <p>本トークンは実験的なものであり、テストおよび教育目的のみに提供されています。</p>
  <p>本プロジェクトおよびトークンは、投資商品または金融商品を意図するものではありません。</p>

</main>

<footer>
  <p>© 2026 荻田力 / chikaraogita</p>
  <p><a href="index.html">← Back to Landing Page</a></p>
</footer>

<script>
  function copyCA() {
    const caText = document.getElementById("ca").innerText;
    navigator.clipboard.writeText(caText).then(() => {
      alert("Contract Address copied: " + caText);
    });
  }
</script>

</body>
</html>
