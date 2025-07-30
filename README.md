<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Boutique de Kenny</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 1em;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .product {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 10px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 12px;
      background-color: #25D366;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue sur la boutique de Kenny</h1>
    <p>Commandez vos produits directement par WhatsApp 📦</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f" alt="Produit 1">
      <h3>Chaussure Homme</h3>
      <p>$29.99</p>
      <a class="btn" href="https://wa.me/50935196415?text=Je%20veux%20acheter%20la%20chaussure%20homme">Commander</a>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1593032465171-c9dffbfa8e0f" alt="Produit 2">
      <h3>Chaussure Femme</h3>
      <p>$34.99</p>
      <a class="btn" href="https://wa.me/50935196415?text=Je%20veux%20acheter%20la%20chaussure%20femme">Commander</a>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1600180758890-6b94519d82c5" alt="Produit 3">
      <h3>T-shirt Homme</h3>
      <p>$14.99</p>
      <a class="btn" href="https://wa.me/50935196415?text=Je%20veux%20acheter%20le%20T-shirt%20homme">Commander</a>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30" alt="Produit 4">
      <h3>Montre Femme</h3>
      <p>$19.99</p>
      <a class="btn" href="https://wa.me/50935196415?text=Je%20veux%20acheter%20la%20montre%20femme">Commander</a>
    </div>
  </section>
</body>
</html>
