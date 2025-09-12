<h1 align="center">🌿 Shopify Learning Theme</h1>
<p align="center" style="font-size:16px; color:#555;">
A clean and structured Shopify theme built for <b>learning Shopify Liquid, theme structure, and development</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Shopify-Liquid-green?style=flat-square" alt="Shopify">
  <img src="https://img.shields.io/badge/Status-Learning-yellow?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License">
</p>

<hr/>

<h2>📚 What is this?</h2>
<p>This repository contains a lightweight Shopify theme intended for <b>learning and experimentation</b> — not for production. It demonstrates:</p>
<ul>
  <li>Liquid templates (layout, templates, sections, snippets)</li>
  <li>Theme folder structure and assets (CSS/JS/images)</li>
  <li>Examples of product, collection, and cart pages</li>
  <li>How to use Shopify CLI to preview and push themes</li>
</ul>

<h2>⚙️ Features</h2>
<ul>
  <li>📝 Well-commented Liquid examples</li>
  <li>🔄 Reusable snippets and sections</li>
  <li>🎨 Simple responsive CSS starter</li>
  <li>⚡ Easy local development with Shopify CLI</li>
</ul>

<h2>🚀 Quick Start</h2>
<p>Clone this repo and serve it locally:</p>
<pre>
<code>
git clone &lt;your-gitlab-repo-url&gt;
cd shopify-learning-theme
shopify theme serve
</code>
</pre>

<p>Or push your existing theme folder to GitLab:</p>
<pre>
<code>
git init
git add .
git commit -m "Initial commit"
git remote add origin https://gitlab.com/&lt;username&gt;/&lt;repo&gt;.git
git branch -M main
git push -u origin main
</code>
</pre>

<h2>🧭 Repository Structure</h2>
<pre>
<code>
/assets      - css, js, images
/config      - theme settings and presets
/layout      - theme.liquid and alternate layouts
/templates   - index, product, collection, cart
/sections    - customizable page sections
/snippets    - reusable Liquid fragments
</code>
</pre>

<h2>💡 Tips for Learners</h2>
<ul>
  <li>Start with <code>/layout/theme.liquid</code> to understand how the theme is structured.</li>
  <li>Explore <code>product</code>, <code>collection</code>, and <code>cart</code> objects.</li>
  <li>Use <code>shopify theme serve</code> to live preview changes.</li>
</ul>

<h2>📌 Note</h2>
<p style="background:#fff8b3; padding:10px; border-left:4px solid #f1c40f;">
<strong>Educational use only:</strong> This theme is built for learning purposes. 
Do not use it as-is for production without auditing.
</p>

<h2>🤝 Contributing</h2>
<p>Contributions are welcome! Open an issue or submit a merge request with improvements or fixes.</p>

<h2>📄 License</h2>
<p>Distributed under the MIT License. See <code>LICENSE</code> for details.</p>

<p align="center"><i>Created by Kuldeep — Happy Learning! 🚀</i></p>
