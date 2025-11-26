# Hello-world-this-is-me-Hina
This is my first repository on GitHub
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Hina — CV</title>
  <meta name="description" content="Hina — Professional CV / Resume">
  <style>
    :root{
      --accent:#0b74de;
      --muted:#6b7280;
      --bg:#f7f9fc;
      --card:#ffffff;
      --radius:12px;
      --max-width:900px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:#0f1724;display:flex;align-items:center;justify-content:center;padding:32px}
    .wrap{width:100%;max-width:var(--max-width)}
    .card{background:var(--card);border-radius:var(--radius);padding:28px;box-shadow:0 6px 20px rgba(12,15,22,0.08)}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#5ad0ff);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:28px}
    h1{margin:0;font-size:28px}
    .role{color:var(--muted);margin-top:6px}

    .grid{display:grid;grid-template-columns:1fr 2fr;gap:22px;margin-top:22px}
    @media (max-width:800px){.grid{grid-template-columns:1fr;}}

    .side{padding:16px;background:#fbfdff;border-radius:10px}
    .section{margin-bottom:18px}
    .section h3{margin:0 0 10px 0;font-size:14px;color:var(--muted);letter-spacing:0.6px}
    .info p{margin:6px 0;color:#111827}
    .muted{color:var(--muted);font-size:13px}

    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:#eef6ff;color:var(--accent);font-weight:600;font-size:13px;margin:6px 6px 0 0}

    .main-section h2{margin:0 0 12px 0;font-size:18px}
    .item{padding:12px 0;border-bottom:1px dashed #eef2f7}
    .item:last-child{border-bottom:0}
    .item h4{margin:0;font-size:15px}
    .item .meta{font-size:13px;color:var(--muted);margin-top:6px}
    .desc{margin-top:8px;color:#111827}

    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .skill{background:#f3f6fb;border-radius:8px;padding:8px 10px;font-size:13px}

    .contact a{display:block;text-decoration:none;color:var(--accent);margin:6px 0}

    .download{margin-left:auto}
    .row{display:flex;align-items:center}
    .small{font-size:13px;color:var(--muted)
