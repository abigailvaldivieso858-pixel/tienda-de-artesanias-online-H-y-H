# tienda-de-artesanias-online-H-y-H
tienda online
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda de Artesanías | H y H Artesanías</title>

  <!-- SEO -->
  <meta name="description" content="H y H Artesanías: piezas únicas hechas a mano con amor y dedicación. Cuadros, decoraciones y más.">
  <meta property="og:title" content="Tienda de Artesanías | H y H Artesanías">
  <meta property="og:description" content="Arte hecho con amor y dedicación. Encuentra artesanías hechas a mano.">
  <meta property="og:image" content="pintura1.jpg">
  <meta property="og:type" content="website">

  <!-- Archivos -->
  <link rel="stylesheet" href="estilos.css">
  <link rel="icon" href="icono.png" type="image/png">
</head>

<body>

  <!-- HEADER -->
  <header class="header">
    <div class="contenedor">
      <h1 class="logo">H y H Artesanías</h1>
      <p class="slogan">Arte hecho con amor y dedicación</p>
    </div>
  </header>

  <!-- NAVBAR -->
  <nav class="navbar" aria-label="Navegación principal">
    <ul class="menu">
      <li><a href="#catalogo">Catálogo</a></li>
      <li><a href="#contacto">Contáctanos</a></li>
      <li><a href="#encargos">Encarga tu diseño</a></li>
    </ul>
  </nav>

  <!-- CONTENIDO -->
  <main class="contenido">
    
    <!-- CUADROS -->
    <section id="catalogo" aria-labelledby="titulo-cuadros">
      <h2 id="titulo-cuadros">Cuadros Artesanales</h2>

      <div class="galeria">

        <figure class="producto">
          <img src="pintura1.jpg" alt="Cuadro con ave entre flores"
               onclick="mostrarVista('pintura1.jpg', 'Cuadro con ave entre flores', 35)">
          <figcaption>
            <h3>Cuadro con ave entre flores</h3>
            <span class="precio">$35.00</span>
          </figcaption>
        </figure>

        <figure class="producto">
          <img src="pintura2.jpg" alt="Cuadro colorido de ave"
               onclick="mostrarVista('pintura2.jpg', 'Cuadro colorido de ave', 40)">
          <figcaption>
            <h3>Cuadro colorido de ave</h3>
            <span class="precio">$40.00</span>
          </figcaption>
        </figure>

        <figure class="producto">
          <img src="pintura3.jpg" alt="Paisaje con ave amarilla"
               onclick="mostrarVista('pintura3.jpg', 'Paisaje con ave amarilla', 30)">
          <figcaption>
            <h3>Paisaje con ave amarilla</h3>
            <span class="precio">$30.00</span>
          </figcaption>
        </figure>

        <figure class="producto">
          <img src="pintura4.jpg" alt="Ave sobre ramas"
               onclick="mostrarVista('pintura4.jpg', 'Ave sobre ramas', 25)">
          <figcaption>
            <h3>Ave sobre ramas</h3>
            <span class="precio">$25.00</span>
          </figcaption>
        </figure>

      </div>

      <!-- LLAVEROS -->
      <h2 style="margin-top: 40px;">Llaveros Artesanales</h2>

      <div class="galeria">

        <figure class="producto">
          <img src="llavero-botella.jpg"
               alt="Llavero artesanal de hombre abrazando botella"
               onclick="mostrarVista('llavero-botella.jpg', 'Llavero hombre con botella', 1.50)">
          <figcaption>
            <h3>Llavero hombre con botella</h3>
            <span class="precio">$1.50</span>
          </figcaption>
        </figure>

        <figure class="producto">
          <img src="llavero-sombrero.jpg"
               alt="Llavero artesanal en forma de sombrero"
               onclick="mostrarVista('llavero-sombrero.jpg', 'Llavero sombrero de cuero', 1.50)">
          <figcaption>
            <h3>Llavero sombrero de cuero</h3>
            <span class="precio">$1.50</span>
          </figcaption>
        </figure>

        <figure class="producto">
          <img src="llavero-corazones.jpg"
               alt="Llavero artesanal con corazones y flores"
               onclick="mostrarVista('llavero-corazones.jpg', 'Llavero corazón con flores', 1.50)">
          <figcaption>
            <h3>Llavero corazón con flores</h3>
            <span class="precio">$1.50</span>
          </figcaption>
        </figure>

        <figure class="producto">
          <img src="llavero-coca.jpg"
               alt="Llavero artesanal con botella de Coca-Cola y snack"
               onclick="mostrarVista('llavero-coca.jpg', 'Llavero Coca-Cola con snack', 1.50)">
          <figcaption>
            <h3>Llavero Coca-Cola con snack</h3>
            <span class="precio">$1.50</span>
          </figcaption>
        </figure>

      </div>

    </section>

    <!-- MODAL -->
    <div id="vistaPrevia" class="modal" role="dialog" aria-modal="true" onclick="cerrarVista()">
      <div class="modal-contenido" onclick="event.stopPropagation()">
        <button class="cerrar" onclick="cerrarVista()" aria-label="Cerrar vista previa">×</button>
        <img id="imagenVista" src="" alt="Vista previa del producto">
        <h3 id="tituloVista"></h3>
        <p id="precioVista"></p>
      </div>
    </div>

  </main>

  <!-- FOOTER -->
  <footer class="footer" id="contacto">
    <div class="contenedor">
      <p>© 2025 <strong>H y H Artesanías</strong> — Todos los derechos reservados.</p>
      <p>Diseñado con ❤️ en El Salvador</p>
    </div>
  </footer>

</body>
</html>
