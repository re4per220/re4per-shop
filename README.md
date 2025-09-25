<!doctype html>
<html lang="tr">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Re4per Shop</title>
  <meta name="description" content="Oyun içi eşya kataloğu. Sadece görseller, isim ve fiyat gösterimi.">
  <style>
    :root{--bg:#0f1720;--card:#0b1220;--accent:#6ee7b7;--muted:#94a3b8;--glass:rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,Arial;background:linear-gradient(180deg,#071028 0%,#081427 100%);color:#e6eef8;min-height:100vh}
    .container{max-width:1100px;margin:28px auto;padding:20px;text-align:center}
    h1{margin:0;font-size:2rem;color:var(--accent)}
    .items{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:14px;margin-top:28px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:12px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03);display:flex;flex-direction:column;align-items:center}
    .thumb{width:100%;height:140px;border-radius:10px;background-size:cover;background-position:center;margin-bottom:10px}
    .name{font-weight:600;margin-bottom:6px}
    .price{background:rgba(0,0,0,0.25);padding:6px 8px;border-radius:8px;font-weight:700}
    @media (max-width:420px){.thumb{height:120px}}
  </style>
</head>
<body>
  <div class="container">
    <h1>Re4per Shop</h1>

    <div class="items">
      <div class="card">
        <div class="thumb" style="background-image:url('https://picsum.photos/seed/sword/600/400')"></div>
        <div class="name">Ejderha Kılıcı</div>
        <div class="price">1200 Ⱡ</div>
      </div>

      <div class="card">
        <div class="thumb" style="background-image:url('https://picsum.photos/seed/armor/600/400')"></div>
        <div class="name">Gece Zırhı</div>
        <div class="price">800 Ⱡ</div>
      </div>

      <div class="card">
        <div class="thumb" style="background-image:url('https://picsum.photos/seed/ring/600/400')"></div>
        <div class="name">Şans Yüzüğü</div>
        <div class="price">450 Ⱡ</div>
      </div>
    </div>
  </div>
</body>
</html>
