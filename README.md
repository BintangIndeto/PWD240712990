<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <title>Bintang Indeto – Landing Page</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    :root{ --bg:#0f172a; --card:#111827; --ink:#e5e7eb; --muted:#9ca3af; --accent:#22d3ee; }
    *{box-sizing:border-box}
    body{
      margin:0; font:16px/1.6 system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color:var(--ink);
      background:radial-gradient(1200px 800px at 10% -10%, #1f2937, #0b1020), var(--bg);
    }
    header{padding:48px 20px 16px; text-align:center}
    h1{margin:0 0 10px; font-size:clamp(28px,4vw,40px); letter-spacing:.4px}
    p.lead{margin:0 auto; max-width:780px; color:var(--muted)}
    .grid{
      display:grid; gap:20px; padding:28px 20px 60px; max-width:980px; margin:0 auto;
      grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    }
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,.04), rgba(0,0,0,.08));
      border:1px solid rgba(255,255,255,.08); border-radius:18px; padding:22px;
      box-shadow:0 10px 30px rgba(0,0,0,.25);
      transition:.2s transform ease, .2s box-shadow ease, .2s border-color ease;
    }
    .card:hover{transform:translateY(-3px); box-shadow:0 16px 40px rgba(0,0,0,.35); border-color:rgba(255,255,255,.14)}
    .eyebrow{font-size:12px; letter-spacing:.18em; text-transform:uppercase; color:var(--muted)}
    .title{margin:.25rem 0 8px; font-size:22px}
    ul{margin:.4rem 0 1rem 1.1rem; padding:0}
    li{margin:.15rem 0; color:var(--muted)}
    .actions{display:flex; gap:10px; flex-wrap:wrap}
    .btn{
      display:inline-block; padding:10px 14px; border-radius:12px; text-decoration:none; font-weight:600;
      border:1px solid rgba(255,255,255,.14); background:#0b1222; color:var(--ink);
    }
    .btn:hover{border-color:var(--accent); box-shadow:0 0 0 3px rgba(34,211,238,.15) inset}
    .btn.primary{background:linear-gradient(180deg, #0ea5e9, #06b6d4); color:#06202a; border:none}
    footer{padding:18px 20px 40px; text-align:center; color:var(--muted)}
    code{background:rgba(255,255,255,.06); padding:.15rem .35rem; border-radius:6px}
  </style>
</head>
<body>

<header>
  <h1>Bintang Indeto – Landing Page</h1>
  <p class="lead">Klik tombol di bawah untuk membuka tugas yang sudah kamu upload ke repo.</p>
</header>

<main class="grid">
  <section class="card">
    <div class="eyebrow">Tugas 1</div>
    <h2 class="title">Form – Activity Week 5</h2>
    <ul>
      <li>File: <code>docs/soal1/act5_form_12990.xml</code></li>
      <li>XHTML/XML form – input dasar</li>
    </ul>
    <div class="actions">
      <!-- Link ke file di GitHub Pages / repo -->
      <a class="btn primary" href="docs/soal1/act5_form_12990.xml">Buka Tugas 1</a>
      <!-- Opsional: link ke kode di GitHub (ganti USERNAME & REPO) -->
      <a class="btn" href="https://github.com/USERNAME/REPO/blob/main/docs/soal1/act5_form_12990.xml" target="_blank" rel="noopener">Lihat Kode</a>
    </div>
  </section>

  <section class="card">
    <div class="eyebrow">Tugas 2</div>
    <h2 class="title">Reservation Hotel Room</h2>
    <ul>
      <li>File: <code>docs/act5_formHotel2_12990.xml</code></li>
      <li>Data personal, kamar, bed type, breakfast</li>
    </ul>
    <div class="actions">
      <a class="btn primary" href="docs/act5_formHotel2_12990.xml">Buka Tugas 2</a>
      <a class="btn" href="https://github.com/USERNAME/REPO/blob/main/docs/act5_formHotel2_12990.xml" target="_blank" rel="noopener">Lihat Kode</a>
    </div>
  </section>
</main>

</body>
</html>
