# rizz--vintage-streetwear
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rizz Vintage Streetwear</title>
  <link rel="stylesheet" href="styles.css" />
  <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville&family=UnifrakturCook&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <h1 class="logo">Rizz</h1>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Vintage Streetwear Redefined</h2>
      <p>Explore our exclusive blue dress design featuring the bold black Rizz logo.</p>
      <img src="dress.png" alt="Blue Streetwear Dress with Rizz Logo" class="dress-image"/>
      <button class="generate-btn">Regenerate Design</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Rizz Streetwear. All rights reserved.</p>
  </footer>
</body>
</html>
body {
  margin: 0;
  background: #f1ede9;
  font-family: 'Libre Baskerville', serif;
  color: #333;
}

header {
  background: #0a0a0a;
  padding: 20px;
  text-align: center;
}

.logo {
  color: #fff;
  font-family: 'UnifrakturCook', cursive;
  font-size: 3rem;
  margin: 0;
}

.hero {
  padding: 60px 20px;
  text-align: center;
  background: url('https://www.transparenttextures.com/patterns/white-wall-3.png');
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  max-width: 600px;
  margin: 0 auto 20px;
}

.dress-image {
  width: 300px;
  margin: 20px 0;
  border: 8px solid #ccc;
  box-shadow: 0 0 20px rgba(0,0,0,0.1);
}

.generate-btn {
  padding: 12px 24px;
  background-color: #0a0a0a;
  color: white;
  border: none;
  font-family: 'Libre Baskerville', serif;
  cursor: pointer;
}

.generate-btn:hover {
  background-color: #333;
}

footer {
  text-align: center;
  padding: 20px;
  background: #0a0a0a;
  color: white;
  font-size: 0.9rem;
}
