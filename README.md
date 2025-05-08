# Bike-baratas
Vendemos bicis al mejor precio  
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tienda de Bicicletas</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #1e90ff;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      padding: 20px;
    }
    .bike {
      background-color: white;
      border-radius: 10px;
      padding: 15px;
      margin: 15px 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .bike img {
      width: 100%;
      max-width: 400px;
      border-radius: 10px;
    }
    .bike h3 {
      margin: 10px 0 5px;
    }
    .price {
      color: green;
      font-weight: bold;
    }
    .buy-btn {
      display: inline-block;
      background-color: #25D366;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      margin-top: 10px;
      text-decoration: none;
      font-size: 16px;
    }
    footer {
      background-color: #1e90ff;
      color: white;
      text-align: center;
      padding: 15px;
      position: fixed;
      width: 100%;
      bottom: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tienda de Bicicletas</h1>
    <p>¡Encuentra tu próxima bici aquí!</p>
  </header>

  <div class="container">
    <div class="bike">
      <img src="https://via.placeholder.com/400x250.png?text=Bicicleta+1" alt="Bicicleta 1">
      <h3>Mountain Bike X100</h3>
      <p class="price">$450 USD</p>
      <p>Bicicleta todoterreno ideal para aventuras en la montaña.</p>
      <a class="buy-btn" href="https://wa.me/525665193913?text=Hola%2C%20quiero%20comprar%20la%20Mountain%20Bike%20X100.%20%C2%BFPuedes%20darme%20los%20datos%20para%20pagarla%3F" target="_blank">
        Comprar por WhatsApp
      </a>
    </div>

    <div class="bike">
      <img src="https://via.placeholder.com/400x250.png?text=Bicicleta+2" alt="Bicicleta 2">
      <h3>City Bike Eco</h3>
      <p class="price">$300 USD</p>
      <p>Perfecta para moverte por la ciudad con estilo y comodidad.</p>
      <a class="buy-btn" href="https://wa.me/525665193913?text=Hola%2C%20estoy%20interesado%20en%20la%20City%20Bike%20Eco.%20%C2%BFMe%20puedes%20pasar%20los%20datos%20para%20pagarla%3F" target="_blank">
        Comprar por WhatsApp
      </a>
    </div>
  </div>

  <footer>
    &copy; 2025 Tienda de Bicicletas. Todos los derechos reservados.
  </footer>

  <!-- Número de cuenta oculto en el código -->
  <script>
    const cuenta = "4152314404053574";
    // Está oculto, pero puedes usarlo desde JavaScript si lo deseas
    // Ejemplo: navigator.clipboard.writeText(cuenta);
  </script>
</body>
</html>
