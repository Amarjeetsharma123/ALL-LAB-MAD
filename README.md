<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Parul University • README</title>
<style>
  :root{
    --bg1:#4facfe; --bg2:#00f2fe; --bg3:#43e97b; --bg4:#fa709a;
    --card:#ffffff; --text:#1b1f23; --muted:#5b6676; --border:#e9eef6;
    --accent:#0d6efd; --ok:#2aa745;
  }
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;
    font-family:system-ui, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
    display:flex; align-items:center; justify-content:center;
    background:linear-gradient(135deg,var(--bg1),var(--bg2),var(--bg3),var(--bg4));
    background-size:400% 400%;
    animation:bgMove 14s ease-in-out infinite;
    color:var(--text);
  }
  @keyframes bgMove{
    0%{background-position:0% 50%}
    50%{background-position:100% 50%}
    100%{background-position:0% 50%}
  }
  .card{
    width:min(920px,92vw);
    background:color-mix(in oklab, var(--card) 92%, white);
    border:1px solid var(--border);
    border-radius:20px;
    padding:28px 30px;
    box-shadow:0 18px 60px rgba(0,0,0,.18);
    backdrop-filter:blur(6px);
    text-align:center;
  }
  .pill{
    display:inline-block;
    padding:6px 12px;
    border-radius:999px;
    background:#eef4ff;
    color:#274690;
    font-weight:600;
    font-size:13px;
    letter-spacing:.2px;
    margin-bottom:8px;
  }
  h1{font-size:32px; margin:6px 0 2px}
  .meta{margin:0 0 18px; color:var(--muted); font-weight:600}
  .kicker{font-size:14px; color:var(--muted); margin-top:4px}
  hr{border:0; height:1px; background:var(--border); margin:18px 0}
  h2{font-size:22px; margin:12px 0 8px}
  p{margin:6px 0 10px; color:#2e3440}
  ul{list-style: none; padding:0; margin:8px 0 6px}
  ul li{
    padding:8px 12px;
    margin:6px 0;
    background:#f7f9fe;
    border:1px solid var(--border);
    border-radius:10px;
    display:flex; gap:8px; align-items:center; justify-content:center;
  }
  code, pre{
    font-family:ui-monospace, SFMono-Regular, Menlo, Consolas, monospace;
    background:#0f172a; color:#e5e7eb;
    border-radius:12px; border:1px solid #0b1220;
  }
  pre{padding:14px; text-align:left; overflow:auto}
  .badges{display:flex; gap:10px; flex-wrap:wrap; justify-content:center; margin:8px 0 2px}
  .badge{padding:6px 10px; border:1px solid var(--border); border-radius:999px; background:#ffffff}
  .footer{
    margin-top:14px; font-size:13px; color:var(--muted)
  }
  .cta{
    display:inline-block; margin-top:10px;
    padding:10px 16px; border-radius:10px; border:0; cursor:pointer;
    background:var(--accent); color:#fff; font-weight:600;
    box-shadow:0 8px 24px rgba(13,110,253,.25);
  }
  .cta.secondary{
    background:transparent; color:var(--accent); border:1px solid #cfe0ff; box-shadow:none;
  }
  .grid{
    display:grid; gap:12px; grid-template-columns:repeat(auto-fit, minmax(240px,1fr));
    text-align:left;
  }
  .card-lite{
    background:#ffffff; border:1px solid var(--border); border-radius:14px; padding:14px;
  }
</style>
</head>
<body>
  <main class="card" role="main" aria-label="Parul University Readme">
    <span class="pill">📘 Parul University</span>
    <h1><strong>Parul University</strong></h1>
    <p class="meta">👩‍🏫 Faculty: <strong>Prof. Renuka Ma'am</strong></p>
    <p class="kicker">👨‍💻 Created by <strong>Amarjeet Sharma</strong></p>

    <hr />

    <h2>🚀 File Upload & Download Dashboard</h2>
    <p>Clean, simple and functional dashboard to <strong>upload files</strong> and <strong>download stored files</strong> with a modern animated background and glassy card UI.</p>

    <div class="badges">
      <span class="badge">HTML5</span>
      <span class="badge">CSS3</span>
      <span class="badge">JavaScript</span>
      <span class="badge">Responsive UI</span>
    </div>

    <hr />

    <div class="grid">
      <section class="card-lite">
        <h2>✅ Features</h2>
        <ul>
          <li>✨ Simple & clean UI</li>
          <li>⬆️ Upload any file type</li>
          <li>⬇️ Download uploaded files</li>
          <li>🧾 Auto-generated file list</li>
          <li>🌈 Animated gradient background</li>
          <li>📱 Responsive design</li>
        </ul>
      </section>

      <section class="card-lite">
        <h2>📂 Project Structure</h2>
        <pre><code>/project-folder
│
├── index.html
└── (Uploaded files stored in browser memory)</code></pre>
      </section>

      <section class="card-lite">
        <h2>💡 Technologies Used</h2>
        <ul>
          <li><strong>HTML5</strong> for structure</li>
          <li><strong>CSS3</strong> for visuals</li>
          <li><strong>JavaScript</strong> for interactions</li>
          <li>Minimal, modern UI</li>
        </ul>
      </section>
    </div>

    <hr />

    <h2>📸 Preview</h2>
    <p>Beautiful animated gradient background with a centered glass-card layout.</p>

    <hr />

    <h2>🙌 Credits</h2>
    <p>Developed as part of Parul University practical work under the guidance of <strong>Prof. Renuka Ma'am</strong>.</p>
    <p><strong>Created by Amarjeet Sharma</strong></p>

    <button class="cta" onclick="window.scrollTo({top:0,behavior:'smooth'})">Back to Top</button>
    <button class="cta secondary" onclick="alert('All the best, Amarjeet!')">Say Hi 👋</button>

    <p class="footer">© <span id="yr"></span> Parul University • For academic use</p>
  </main>

  <script>
    document.getElementById('yr').textContent = new Date().getFullYear();
  </script>
</body>
</html>
