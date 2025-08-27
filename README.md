# Tienda-La-Bella
/*Tu tienda virtual*/

<!DOCTYPE html>
<html>
  <head>
    <title>Tienda La Bella</title>
  </head>
  <body>
      <h1 class="title">Tienda La Bella! </h1>
        <img src="ruta/de/tu/imagen.jpg" alt="Descripción de la imagen">

              <h1>Bienvenido a mi tienda virtual</h1>
        <p>La mejor tienda virtual con ropa de calidad con muy buenos precios.</p>
        <a href="https://www.instagram.com/bellag01_?igsh=MWEzNmY3OHJ4dTgzcg%3D%3D&utm_source=qr">Visita mi pagina de instagram</a>
        
           <p>Contactanos:</p>
            <form action="/procesar_formulario.php" method="post">
        <!-- Campos del formulario irán aquí -->
    </form>
    
        <form action="/procesar_formulario.php" method="post">
        <label for="nombre">Nombre:</label><br>
        <input type="text" id="nombre" name="nombre"><br>

        <label for="email">Correo electrónico:</label><br>
        <input type="email" id="email" name="email"><br>

        <label for="mensaje">Mensaje:</label><br>
        <textarea id="mensaje" name="mensaje"></textarea><br>
    </form>
    <button type="submit">Enviar</button>
    </form>


  </body>
</html>
