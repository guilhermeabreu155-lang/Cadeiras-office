<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cadeiras OfficePro</title>
  <style>
    /* Reset básico */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #1a73e8;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
      background-color: #1565c0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      text-align: center;
      padding: 50px 20px;
      background: url('https://images.unsplash.com/photo-1585386959984-a415522d6f06?auto=format&fit=crop&w=1470&q=80') no-repeat center center;
      background-size: cover;
      color: white;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .product-card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
      transition: transform 0.2s;
    }

    .product-card:hover {
      transform: scale(1.05);
    }

    .product-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .product-card h3 {
      margin: 15px 0 10px 0;
    }

    .product-card p {
      padding: 0 10px 10px 10px;
      font-size: 0.9rem;
    }

    .product-card button {
      background-color: #1a73e8;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-bottom: 15px;
      cursor: pointer;
      border-radius: 5px;
      transition: background-color 0.2s;
    }

    .product-card button:hover {
      background-color: #1565c0;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #1a73e8;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Cadeiras OfficePro</h1>
    <p>Conforto e qualidade para seu escritório</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#produtos">Produtos</a>
    <a href="#contato">Contato</a>
  </nav>

  <section class="hero" id="home">
    <h1>Encontre a cadeira perfeita</h1>
    <p>Ergonômica, moderna e confortável para longas horas de trabalho.</p>
  </section>

  <section class="products" id="produtos">
    <div class="product-card">
      <img src="https://images.unsplash.com/photo-1616627982296-6fa44f5807b5?auto=format&fit=crop&w=800&q=80" alt="Cadeira Executiva">
      <h3>Cadeira Executiva</h3>
      <p>Estilo moderno, ajuste de altura e apoio lombar reforçado.</p>
      <button>Comprar</button>
    </div>
    <div class="product-card">
      <img src="https://images.unsplash.com/photo-1585238342027-48da0b4a52e7?auto=format&fit=crop&w=800&q=80" alt="Cadeira Gamer">
      <h3>Cadeira Gamer</h3>
      <p>Design ergonômico e estofado premium, ideal para longas sessões de jogo.</p>
      <button>Comprar</button>
    </div>
    <div class="product-card">
      <img src="https://images.unsplash.com/photo-1616627982300-42b4f8f8f11b?auto=format&fit=crop&w=800&q=80" alt="Cadeira de Escritório Simples">
      <h3>Cadeira Simples</h3>
      <p>Prática e confortável, perfeita para home office ou escritório.</p>
      <button>Comprar</button>
    </div>
  </section>

  <footer id="contato">
    <p>© 2025 Cadeiras OfficePro - Todos os direitos reservados</p>
    <p>Contato: contato@officepro.com</p>
  </footer>

</body>
</html>
