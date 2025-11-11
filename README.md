# Sialword pk
Online services 
<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Signup — Sialword</title>
  <meta name="description" content="Simple responsive signup page export — ready to host on Netlify / GitHub Pages / 000webhost" />
  <style>
    :root{
      --bg:#f6f7fb; --card:#ffffff; --accent:#2563eb; --muted:#6b7280; --radius:14px;
      --maxw:720px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      background:linear-gradient(180deg,#eef2ff 0%,var(--bg) 100%); color:#111827;
      -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale;
      display:flex; align-items:center; justify-content:center; padding:32px;
    }
    .wrap{width:100%; max-width:var(--maxw);}
    .card{
      background:var(--card); border-radius:var(--radius); box-shadow:0 8px 30px rgba(2,6,23,0.08);
      overflow:hidden; display:flex; flex-direction:row; min-height:420px;
    }
    .aside{flex:1.05; background-image:linear-gradient(180deg, rgba(37,99,235,0.95), rgba(59,130,246,0.95)), url(''); background-size:cover; color:#fff; padding:36px; display:flex; flex-direction:column; justify-content:center; gap:18px}
    .aside h1{margin:0; font-size:28px; letter-spacing: -0.02em}
    .aside p{margin:0; opacity:0.95}
    .main{flex:1.2; padding:28px 28px;}
    .brand{display:flex; 
