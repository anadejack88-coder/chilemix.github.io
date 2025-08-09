<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Chile Mix — SalsaKids</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Pacifico&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#fff;
      --accent-green:#1db954;
      --accent-red:#d42b2b;
      --accent-yellow:#f2b705;
      --muted:#6b7280;
      --card:#ffffffcc;
      --glass: rgba(255,255,255,0.8);
    }
    *{box-sizing:border-box}
    body{font-family:Montserrat,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial; margin:0;background:linear-gradient(180deg,#fff,#f7f9fb); color:#111}
    header{display:flex;align-items:center;justify-content:space-between;padding:18px 32px;background:transparent}
    .brand{display:flex;align-items:center;gap:14px}
    .brand img{height:64px;width:auto;border-radius:8px;box-shadow:0 6px 18px rgba(0,0,0,0.12)}
    .brand h1{font-family:Pacifico, cursive;color:var(--accent-green);margin:0;font-size:22px}
    nav a{margin-left:16px;text-decoration:none;color:var(--muted);font-weight:600}
    nav a.cta{background:linear-gradient(90deg,var(--accent-red),var(--accent-green));color:#fff;padding:10px 14px;border-radius:10px}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:32px;align-items:center;padding:48px 6vw}
    .hero .left{max-width:720px}
    .eyebrow{display:inline-block;padding:6px 10px;border-radius:999px;background:linear-gradient(90deg,var(--accent-red),var(--accent-yellow));color:#fff;font-weight:700;font-size:13px}
    .title{font-size:42px;margin:18px 0 8px;line-height:1.02}
    .title strong{color:var(--accent-red)}
    .subtitle{color:var(--muted);margin-bottom:22px}
    .actions{display:flex;gap:12px}
    button{border:0;padding:12px 16px;border-radius:12px;font-weight:700;cursor:pointer}
    .primary{background:linear-gradient(90deg,var(--accent-red),var(--accent-green));color:#fff}
    .secondary{background:transparent;border:2px solid #eee}
    .hero .card{background:var(--glass);padding:18px;border-radius:16px;box-shadow:0 10px 30px rgba(2,6,23,0.06);display:flex;flex-direction:column;align-items:center}
    .logo-preview{width:100%;max-width:340px;height:220px;display:flex;align-items:center;justify-content:center}
    .logo-preview img{max-width:100%;max-height:100%;object-fit:contain}
    .logo-caption{font-size:13px;color:var(--muted);margin-top:12px}
    .features{display:flex;gap:18px;padding:32px 6vw}
    .feature{flex:1;background:#fff;padding:18px;border-radius:12px;box-shadow:0 6px 20px rgba(2,6,23,0.04)}
    .feature h3{margin:0 0 8px}
    .feature p{margin:0;color:var(--muted)}
    footer{padding:28px 6vw;margin-top:36px;border-top:1px solid #eee;display:flex;justify-content:space-between;align-items:center}
    @media (max-width:900px){
      .hero{grid-template-columns:1fr;}
      .hero .card{order:-1;margin-bottom:12px}
      nav{display:none}
    }
  </style>
</head>
<body>
  <header>
    <div class="brand">
      <img src="WhatsApp Image 2025-08-08 at 10.38.00 PM.jpeg" alt="Chile Mix - Logo">
      <div>
        <h1>Chile Mix</h1>
        <div style="font-size:12px;color:var(--muted);margin-top:3px">SalsaKids • Ritmo y sabor para toda la familia</div>
      </div>
    </div>
    <nav>
      <a href="#about">Nosotros</a>
      <a href="#products">Productos</a>
      <a href="#contact" class="cta">Contacto</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div class="left">
        <span class="eyebrow">Nuevo lanzamiento</span>
        <h2 class="title">Salsas artesanales con <strong>sabor auténtico</strong></h2>
        <p class="subtitle">Chile Mix nace para llevar la tradición mexicana a tu cocina con salsas hechas con ingredientes naturales, sin conservadores, y recetas pensadas para niños y familias.</p>
        <div class="actions">
          <button class="primary">Ver colección</button>
          <button class="secondary">Historia</button>
        </div>
      </div>
      <aside class="card">
        <div class="logo-preview">
          <img src="WhatsApp Image 2025-08-08 at 10.38.00 PM.jpeg" alt="Logo Chile Mix">
        </div>
        <div class="logo-caption">Logo oficial • Usa este archivo en tus etiquetas y redes</div>
      </aside>
    </section>

    <section id="about" class="features">
      <div class="feature">
        <h3>Recetas familiares</h3>
        <p>Desarrolladas con chefs locales y pensadas para los paladares de niños y adultos: balance perfecto entre picante y sabor.</p>
      </div>
      <div class="feature">
        <h3>Ingredientes naturales</h3>
        <p>Chiles seleccionados, vegetales frescos y sin aditivos artificiales — solo lo que tu familia necesita.</p>
      </div>
      <div class="feature">
        <h3>Packaging divertido</h3>
        <p>Etiquetas coloridas con el personaje de la marca, ideales para llamar la atención en punto de venta y redes sociales.</p>
      </div>
    </section>

    <section id="products" style="padding:32px 6vw">
      <h2 style="margin-top:0">Nuestros productos</h2>
      <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;margin-top:12px">
        <div style="background:#fff;padding:14px;border-radius:12px;box-shadow:0 8px 22px rgba(2,6,23,0.04)">
          <div style="height:140px;display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,#fff,#fbfbfb);border-radius:8px;margin-bottom:10px">Imagen</div>
          <strong>Chile Mix Kids - Mild</strong>
          <p style="color:var(--muted);font-size:14px;margin:6px 0 0">Suave y sabrosa, ideal para los más pequeños.</p>
        </div>
        <div style="background:#fff;padding:14px;border-radius:12px;box-shadow:0 8px 22px rgba(2,6,23,0.04)">
          <div style="height:140px;display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,#fff,#fbfbfb);border-radius:8px;margin-bottom:10px">Imagen</div>
          <strong>Chile Mix Original</strong>
          <p style="color:var(--muted);font-size:14px;margin:6px 0 0">El clásico sabor casero con un toque picante equilibrado.</p>
        </div>
        <div style="background:#fff;padding:14px;border-radius:12px;box-shadow:0 8px 22px rgba(2,6,23,0.04)">
          <div style="height:140px;display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,#fff,#fbfbfb);border-radius:8px;margin-bottom:10px">Imagen</div>
          <strong>Chile Mix Picante</strong>
          <p style="color:var(--muted);font-size:14px;margin:6px 0 0">Para los valientes: intensidad y profundidad en cada bocado.</p>
        </div>
      </div>
    </section>

    <section id="contact" style="padding:32px 6vw;background:linear-gradient(90deg,#fff,#f9fff5);border-top:1px solid #eee">
      <h2>Contacto</h2>
      <div style="display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:12px">
        <div>
          <p style="color:var(--muted)">¿Quieres vender Chile Mix en tu tienda o colaborar? Escríbenos y te responderemos a la brevedad.</p>
          <ul style="color:var(--muted);padding-left:20px">
            <li>ventas@chilemix.com</li>
            <li>+52 81 81392500</li>
            <li>Ciudad de México, México</li>
          </ul>
        </div>
        <form style="background:#fff;padding:16px;border-radius:12px;box-shadow:0 8px 20px rgba(2,6,23,0.04)" onsubmit="alert('Formulario simulado — en producción conecta un endpoint');return false;">
          <input required placeholder="Tu nombre" style="width:100%;padding:10px;margin-bottom:8px;border-radius:8px;border:1px solid #eee">
          <input required placeholder="Correo" type="email" style="width:100%;padding:10px;margin-bottom:8px;border-radius:8px;border:1px solid #eee">
          <textarea required placeholder="Mensaje" style="width:100%;padding:10px;border-radius:8px;border:1px solid #eee;min-height:90px"></textarea>
          <div style="text-align:right;margin-top:8px"><button class="primary">Enviar</button></div>
        </form>
      </div>
    </section>
  </main>

  <footer>
    <div style="display:flex;align-items:center;gap:12px">
      <img src="WhatsApp Image 2025-08-08 at 10.38.00 PM.jpeg" alt="logo small" style="height:40px;border-radius:6px">
      <div style="font-size:14px">&copy; <strong>Chile Mix</strong> — SalsaKids 2025</div>
    </div>
    <div style="font-size:13px;color:var(--muted)">Síguenos en redes • Instagram · Facebook</div>
  </footer>

</body>
</html>

