<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Vahtusa</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Vahtusa – a small silver direction in a loud world. A simple mantra practice: sit, think the word, drift, return.">
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #050712;
      --star: #f0ece0;
      --text: #f5f1e6;
      --muted: #b7b3a7;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      min-height: 100vh;
      background: radial-gradient(circle at 50% 15%, #1a2033 0, #050712 55%, #02030a 100%);
      color: var(--text);
      font-family: "Space Grotesk", system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 32px 16px;
    }
    .wrap {
      max-width: 420px;
      width: 100%;
      text-align: center;
    }
    .star {
      width: 80px;
      height: 80px;
      margin: 0 auto 24px;
      border-radius: 50%;
      background:
        radial-gradient(circle at 50% 40%, rgba(255,255,255,0.9) 0, rgba(255,255,255,0) 55%),
        radial-gradient(circle at 50% 50%, rgba(255,255,255,0.35) 0, rgba(255,255,255,0) 70%);
      box-shadow:
        0 0 35px rgba(255,255,255,0.35),
        0 0 90px rgba(140,160,255,0.25);
    }
    h1 {
      font-size: 1.8rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      margin-bottom: 8px;
    }
    .tagline {
      font-size: 0.95rem;
      color: var(--muted);
      margin-bottom: 24px;
    }
    .copy {
      font-size: 0.95rem;
      line-height: 1.6;
      margin-bottom: 28px;
    }
    .buttons {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-bottom: 20px;
    }
    .btn {
      display: block;
      padding: 10px 14px;
      border-radius: 999px;
      border: 1px solid rgba(240,236,224,0.4);
      text-decoration: none;
      color: var(--text);
      font-size: 0.9rem;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      transition: background 0.2s ease, color 0.2s ease, border-color 0.2s ease, transform 0.15s ease;
    }
    .btn.primary {
      background: rgba(240,236,224,0.06);
      border-color: rgba(240,236,224,0.8);
    }
    .btn:hover {
      background: rgba(240,236,224,0.12);
      border-color: rgba(240,236,224,1);
      transform: translateY(-1px);
    }
    .note {
      font-size: 0.75rem;
      color: var(--muted);
      opacity: 0.9;
    }
  </style>
</head>
<body>
  <main class="wrap">
    <div class="star"></div>
    <h1>Vahtusa</h1>
    <p class="tagline">A small silver direction in a loud world.</p>

    <p class="copy">
      A simple mantra practice:<br>
      sit, think the word, drift, return.
    </p>

    <div class="buttons">
      <!-- Update this when the Kindle link is live -->
      <a class="btn primary" href="#" target="_blank" rel="noopener noreferrer">
        Guidebook coming soon
      </a>

      <!-- Put your real IG URL here -->
      <a class="btn" href="https://instagram.com/vahtusa" target="_blank" rel="noopener noreferrer">
        Follow on Instagram
      </a>

      <!-- Put whatever email you want to use here -->
      <a class="btn" href="mailto:hello@vahtusa.com">
        Quiet updates by email
      </a>
    </div>

    <p class="note">
      Guidebook “Come With Me to Vahtusa” by J. J. Marcellus.
    </p>
  </main>
</body>
</html>
