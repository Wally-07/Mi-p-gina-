
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>prINKtealo Mzt</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Inter', sans-serif; background: #fff8f4; color: #222; }
    header { background: #ff6b6b; color: #fff; padding: 1.5rem 2rem; display: flex; justify-content: space-between; align-items: center; }
    header h1 { font-family: 'Playfair Display', serif; font-size: 1.8rem; }
    nav a { color: #fff; text-decoration: none; margin-left: 1.5rem; font-weight: 600; }
    .hero { text-align: center; padding: 4rem 2rem; background: linear-gradient(145deg, #ffb6b6, #ffe0e0); }
    .hero h2 { font-size: 2.8rem; font-family: 'Playfair Display', serif; color: #222; }
    .hero p { margin-top: 1rem; font-size: 1.2rem; }
    .btn { background: #222; color: #fff; padding: 0.75rem 1.5rem; border: none; border-radius: 25px; cursor: pointer; margin-top: 2rem; font-weight: bold; }
    .section { padding: 4rem 2rem; text-align: center; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 2rem; margin-top: 2rem; }
    .product { background: #fff; padding: 1.5rem; border-radius: 10px; box-shadow: 0 5px 10px rgba(0,0,0,0.05); }
    .product h4 { margin: 1rem 0 0.5rem; }
    .product p { font-size: 0.95rem; }
    footer { background: #222; color: #fff; padding: 2rem; text-align: center; }
  </style>
</head>
<body>
  <header>
    <h1>prINKtealo Mzt</h1>
    <nav>
      <a href="#">Inicio</a>
      <a href="#productos">Productos</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Dale vida a tus ideas</h2>
    <p>Plantillas digitales, artículos de impresión y diseño personalizado para creadores como tú.</p>
    <button class="btn">Explora la tienda</button>
  </section>

  <section class="section" id="productos">
    <h3>Productos Destacados</h3>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/220x140" alt="Stickers" style="width:100%; border-radius:8px;">
        <h4>Stickers Creativos</h4>
        <p>Diseños únicos para planners, cuadernos y laptops.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/220x140" alt="Agenda Printable" style="width:100%; border-radius:8px;">
        <h4>Agendas imprimibles</h4>
        <p>Organízate con estilo y practicidad. Listas para descargar.</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/220x140" alt="Posters" style="width:100%; border-radius:8px;">
        <h4>Pósters decorativos</h4>
        <p>Ilustraciones únicas que puedes imprimir en casa.</p>
      </div>
    </div>
  </section>

  <section class="section" id="contacto">
    <h3>Contáctanos</h3>
    <p>¿Tienes una idea o quieres algo personalizado? ¡Escríbenos!</p>
    <form action="https://formspree.io/f/mwkzgeor" method="POST" style="margin-top:2rem; max-width:500px; margin-inline:auto;">
      <input type="text" name="name" placeholder="Tu nombre" required style="width:100%;padding:1rem;margin-bottom:1rem;">
      <input type="email" name="email" placeholder="Tu email" required style="width:100%;padding:1rem;margin-bottom:1rem;">
      <textarea name="message" rows="4" placeholder="Tu mensaje" required style="width:100%;padding:1rem;margin-bottom:1rem;"></textarea>
      <button class="btn" type="submit">Enviar mensaje</button>
    </form>
  </section>

  <footer>
    <p>© 2025 prINKtealo Mzt. Diseñado con tinta y corazón.</p>
    <p>Síguenos en Instagram | TikTok | Facebook</p>
  </footer>
</body>
</html>
