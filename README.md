<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Casino VIP</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0a0f0d;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      background-image: linear-gradient(180deg, #013220, #0a0f0d);
    }
    .container {
      width: 90%;
      max-width: 400px;
      background-color: #012d22;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,255,0,0.3);
      text-align: center;
    }
    h1 {
      color: #00ff99;
    }
    .form-group {
      margin-bottom: 15px;
      text-align: left;
    }
    label {
      display: block;
      margin-bottom: 5px;
      color: #ccc;
    }
    input {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 8px;
      background-color: #1a1f1d;
      color: #fff;
    }
    button {
      width: 100%;
      padding: 12px;
      background-color: #00ff99;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      color: #000;
      cursor: pointer;
    }
    .footer {
      margin-top: 20px;
      font-size: 12px;
      color: #777;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Bienvenido al Casino VIP</h1>
    <p>¡Gana hasta <strong>15000€</strong> en tus primeros depósitos!</p>

    <form>
      <div class="form-group">
        <label for="telefono">Número de teléfono</label>
        <input type="tel" id="telefono" placeholder="+34 600 123 456" required>
      </div>

      <div class="form-group">
        <label for="password">Contraseña</label>
        <input type="password" id="password" placeholder="••••••" required>
      </div>

      <button type="submit">Jugar Ahora</button>
    </form>

    <div class="footer">
      Compatible solo con dispositivos Android.
    </div>
  </div>

</body>
</html>
