<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Juegos de Daza</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f0f0;
      text-align: center;
      margin: 0;
      padding: 0;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 20px 0;
      font-size: 2em;
    }
    .game-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
      gap: 20px;
    }
    .game {
      background: white;
      padding: 20px;
      border-radius: 10px;
      width: 200px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      cursor: pointer;
      transition: transform 0.2s;
    }
    .game:hover {
      transform: scale(1.05);
    }
    iframe {
      border: none;
      width: 400px;
      height: 400px;
      margin-top: 20px;
    }
  </style>
</head>
<body
