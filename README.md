<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Demo XHTML Forms – Landing Page</title>
  <style>
    :root{
      --bg:#0f172a; --card:#111827; --ink:#e5e7eb; --muted:#9ca3af; --accent:#22d3ee;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font:16px/1.6 system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color:var(--ink); background:radial-gradient(1200px 800px at 10% -10%, #1f2937, #0b1020), var(--bg);
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
      border:1px solid rgba(255,255,255,.08);
      border-radius:18px; padding:22px; box-shadow:0 10px 30px rgba(0,0,0,.25);
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
  <h1>Demo XHTML Forms</h1>
  <p class="lead">Halaman muka untuk mengakses dua form tugas: <em>Formulir Registrasi Mahasiswa</em> dan
    <em>Reservation Hotel Room</em>. Klik tombol di bawah untuk membuka halaman masing-masing.</p>
</header>

<main class="grid">
  <section class="card">
    <div class="eyebrow">Tugas 1</div>
    <h2 class="title">Formulir Registrasi Mahasiswa</h2>
    <ul>
      <li>XHTML 1.0 Strict, tabel + input</li>
      <li>Radio (jenis kelamin), select (prodi), file upload</li>
      <li>Checkbox minat &amp; textarea resume</li>
    </ul>
    <div class="actions">
      <a class="btn primary" href="mahasiswa.xhtml">Buka Form</a>
      <a class="btn" href="https://github.com/USERNAME/REPO/blob/main/mahasiswa.xhtml">Lihat Kode</a>
    </div>
  </section>

  <section class="card">
    <div class="eyebrow">Tugas 2</div>
    <h2 class="title">Reservation Hotel Room</h2>
    <ul>
      <li>Data pribadi, detail reservasi</li>
      <li>Pilihan room &amp; bed type, breakfast</li>
      <li>Metode pembayaran, tanggal check-in/out</li>
    </ul>
    <div class="actions">
      <a class="btn primary" href="reservasi-hotel.xhtml">Buka Form</a>
      <a class="btn" href="https://github.com/USERNAME/REPO/blob/main/reservasi-hotel.xhtml">Lihat Kode</a>
    </div>
  </section>
</main>

<footer>
  Simpan file ini sebagai <code>index.html</code> di root repo yang sama dengan
  <code>mahasiswa.xhtml</code> dan <code>reservasi-hotel.xhtml</code>.
</footer>

</body>
</html>
