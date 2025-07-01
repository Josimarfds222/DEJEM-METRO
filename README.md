<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Menu DEJEM - PMESP</title>
  <style>
    body {
      background: #f2f2f2;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .menu {
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
      width: 300px;
    }
    h1 {
      margin-bottom: 20px;
      font-size: 22px;
      color: #333;
    }
    button {
      width: 100%;
      padding: 15px;
      margin: 10px 0;
      font-size: 16px;
      background-color: #2e6da4;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #204d74;
    }
  </style>
</head>
<body>
  <div class="menu">
    <h1>Menu Principal</h1>
    <button onclick="location.href='relatorio_dejem.html'">RELATÓRIO DA DEJEM</button>
    <button onclick="location.href='parte_falta.html'">PARTE DE FALTA</button>
    <button onclick="location.href='escala.html'">ESCALA</button>
  </div>
</body>
</html>
