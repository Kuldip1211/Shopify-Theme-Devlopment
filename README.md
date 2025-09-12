<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>Shopify Learning Theme — README</title>
    <style>
      body{font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; line-height:1.6; color:#111; padding:24px;}
      header{display:flex;align-items:center;gap:16px}
      h1{margin:0;font-size:28px}
      p.lead{margin:8px 0 20px;color:#444}
      .badges img{height:20px;margin-right:8px}
      section{margin-top:18px}
      pre{background:#f6f8fa;padding:12px;border-radius:6px;overflow:auto}
      code{font-family: 'Courier New', monospace;}
      ul{margin:8px 0 0 20px}
      .note{background:#fff7cc;padding:10px;border-left:4px solid #ffd54f}
    </style>
  </head>
  <body>
    <header>
      <div>
        <h1>🌿 Shopify Learning Theme</h1>
        <p class="lead">A minimal, well-structured Shopify theme designed as a learning resource for developers exploring Shopify Liquid, theme structure, and local development with Shopify CLI.</p>
        <div class="badges">
          <!-- Replace badge images/links as needed -->
          <img src="https://img.shields.io/badge/Shopify-Learning-brightgreen" alt="shopify">
          <img src="https://img.shields.io/badge/Status-Experimental-yellow" alt="status">
        </div>
      </div>
    </header>

    <section>
      <h2>📚 What is this?</h2>
      <p>This repository contains a lightweight Shopify theme intended for learning and experimentation — not for production. It demonstrates:</p>
      <ul>
        <li>Liquid templates (layout, templates, sections, snippets)</li>
        <li>Theme folder structure and assets (CSS/JS/images)</li>
        <li>Examples of product, collection, and cart pages</li>
        <li>How to use Shopify CLI to preview and push themes</li>
      </ul>
    </section>

    <section>
      <h2>⚙️ Features</h2>
      <ul>
        <li>Well-commented Liquid examples</li>
        <li>Reusable snippets and sections</li>
        <li>Simple responsive CSS starter</li>
        <li>Instructions for local development with Shopify CLI</li>
      </ul>
    </section>

    <section>
      <h2>🚀 Quick Start (local)</h2>
      <p>Open a terminal in your project folder and run:</p>
      <pre><code>git clone &lt;your-gitlab-repo-url&gt;
cd shopify-learning-theme
# Install Shopify CLI (see shopify.dev for instructions)
shopify theme serve
</code></pre>
      <p>If you already have a theme folder, use:</p>
      <pre><code>git init
git add .
git commit -m "Initial commit"
git remote add origin https://gitlab.com/&lt;username&gt;/&lt;repo&gt;.git
git branch -M main
git push -u origin main
</code></pre>
    </section>

    <section>
      <h2>🧭 Repository Structure</h2>
      <pre><code>/assets         - css, js, images
/config         - theme settings and presets
/layout         - theme.liquid and alternate layouts
/templates      - index, product, collection, cart
/sections       - customizable page sections
/snippets       - small reusable Liquid fragments
</code></pre>
    </section>

    <section>
      <h2>💡 Tips for Learners</h2>
      <ul>
        <li>Start with <code>/layout/theme.liquid</code> and follow how header/footer are included via snippets.</li>
        <li>Open a product template and trace the Liquid objects like <code>product</code>, <code>collection</code>, and <code>cart</code>.</li>
        <li>Use Shopify CLI's <code>shopify theme serve</code> to live-reload changes while learning.</li>
      </ul>
    </section>

    <section>
      <h2>📌 Note</h2>
      <div class="note">
        <strong>Educational use only:</strong> This theme is built to teach concepts. Do not use it as-is for production stores without auditing, accessibility checks, and performance optimization.
      </div>
    </section>

    <section>
      <h2>🤝 Contributing</h2>
      <p>Contributions are welcome — open an issue or submit a merge request with improvements, examples, or fixes.</p>
    </section>

    <section>
      <h2>📄 License</h2>
      <p>Distributed under the MIT License. See <code>LICENSE</code> for details.</p>
    </section>

    <footer style="margin-top:26px;color:#666;font-size:13px">
      <p>Created by Kuldeep — happy learning! 🚀</p>
    </footer>
  </body>
</html>
