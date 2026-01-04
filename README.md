index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Trem Bão Deli</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      text-align: center;
    }
    header {
      background: #7a1c1c;
      color: white;
      padding: 20px;
    }
    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .galeria img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #222;
      color: white;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Trem Bão Deli</h1>
  <p>Comida boa, bem servida e com gosto de casa</p>
</header>

<section class="galeria">
  <img src="z.jpg">
  <img src="z2.jpg">
  <img src="z3.jpg">
  <img src="z4.jpg">
  <img src="z5.jpg">
  <img src="z6.jpg">
  <img src="z7.jpg">
  <img src="z8.jpg">
</section>

<footer>
  <p>Av. Embaixador Abelardo Bueno, 3050 – Barra Olímpica – RJ</p>
  <p>© Trem Bão Deli</p>
</footer>

</body>
</html>
