<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Productos del Artesano</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      display: flex;
    }
    .container {
      display: flex;
      margin: 20px;
      width: 100%;
      gap: 20px;
    }
    .profile {
      width: 25%;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      padding: 20px;
    }
    .profile img {
      width: 100%;
      border-radius: 10px;
    }
    .profile h2 {
      text-align: center;
      margin: 15px 0 5px;
    }
    .contact-info {
      text-align: center;
      font-size: 0.9em;
      margin-bottom: 15px;
      color: #444;
    }
    .contact-info a {
      display: block;
      color: #555;
      text-decoration: none;
      margin-top: 4px;
    }
    .contact-info a:hover {
      text-decoration: underline;
    }
    .history {
      background-color: #ffe8dd;
      padding: 10px;
      border-left: 5px solid #c84c36;
      border-radius: 5px;
    }
    .history strong {
      display: block;
      margin-bottom: 5px;
      color: #c84c36;
    }
    .products {
      width: 75%;
    }
    .products h2 {
      margin-bottom: 20px;
      color: #772727;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }
    .product-card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      overflow: hidden;
      display: flex;
      flex-direction: column;
    }
    .product-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    .product-card h3 {
      margin: 10px;
      font-size: 1.1em;
    }
    .product-card p {
      margin: 0 10px 10px;
      font-size: 0.9em;
      color: #444;
    }
    .product-card button {
      margin: 10px;
      padding: 8px;
      background-color: #8b3e3e;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .product-card button:hover {
      background-color: #6d2f2f;
    }
  </style>
</head>
<body>
<div class="container">
  <!-- Columna de perfil -->
  <div class="profile">
    <img src="https://i.imgur.com/N1m5zct.jpg" alt="Foto Carmen Rodríguez" />
    <h2>Martha Lucia Aguirre</h2>
    <div class="contact-info">
      <a href="mailto:creacionesmalu@gmail.com">creacionesmalu@gmail.com</a>
      <a href="tel:+573114931433">Tel: 311 4931433</a>
      <a href="https://www.instagram.com/creaciones_malu72" target="_blank">Instagram: @creaciones_malu72</a>
    </div>
    <div class="history">
      <strong>Historia:</strong>
      <p>Martha Aguirre es una artesana apasionada por su oficio, una mujer fuerte y resiliente que ha encontrado en el arte una forma de expresar su alma. Junto a su esposo, enfrenta cada día con valentía, superando juntos una dura prueba: hace cinco años, él perdió la visión.
Lejos de detenerse, esta pareja convirtió el desafío en una oportunidad para fortalecer su vínculo. Hoy, él colabora activamente en el proceso de creación, aportando con sus manos y su corazón a la elaboración de las manillas artesanales. Para ambos, la artesanía no es solo un trabajo, sino una terapia que les permite sanar, compartir y seguir adelante.
Su historia es un testimonio de amor, compromiso y esperanza, reflejado en cada pieza que crean juntos.
      </p>
    </div>
  </div>
  <!-- Columna de productos -->
  <div class="products">
    <h2>Productos de Creaciones Malu</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://i.imgur.com/hS8sWez.jpg" alt="Camino de mesa tejido" />
        <h3>Camino de mesa tejido</h3>
        <p>Diseño elaborado con telar de pedal, colores naturales.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="https://i.imgur.com/NfQbXJL.jpg" alt="Bolso artesanal" />
        <h3>Bolso artesanal</h3>
        <p>Bolso tejido con fibras de fique, decorado a mano.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="https://i.imgur.com/Z7dIp1m.jpg" alt="Tapiz decorativo" />
        <h3>Tapiz decorativo</h3>
        <p>Inspirado en paisajes del Líbano Tolima, ideal para interiores.</p>
        <button>Ver más</button>
      </div>
      <div class="product-card">
        <img src="https://i.imgur.com/dH5A9Fa.jpg" alt="Monedero Wayuu" />
        <h3>Monedero Wayuu</h3>
        <p>Colores vibrantes, tejidos con diseño geométrico tradicional.</p>
        <button>Ver más</button>
      </div>
    </div>
  </div>
</div>
</body>
</html>
