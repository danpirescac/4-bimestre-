# 4-bimestre-
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Site Responsivo com Swiper.js</title>
  <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Meu Site Responsivo</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h2>Bem-vindo ao Slider</h2>
    <div class="swiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide">Slide 1</div>
        <div class="swiper-slide">Slide 2</div>
        <div class="swiper-slide">Slide 3</div>
      </div>
      <!-- Botões de navegação -->
      <div class="swiper-button-prev"></div>
      <div class="swiper-button-next"></div>
      <div class="swiper-pagination"></div>
    </div>
  </section>

  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>Este é um site responsivo com um slider moderno.</p>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <form>
      <input type="text" placeholder="Seu Nome" required>
      <input type="email" placeholder="Seu Email" required>
      <textarea placeholder="Sua Mensagem" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2024 Meu Site Responsivo</p>
  </footer>

  <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
  <script src="script.js"></script>
</body>
</html>
