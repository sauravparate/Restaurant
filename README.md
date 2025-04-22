# Restaurant
#html code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Delicious Bites</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Delicious Bites</h1>
    <p>Fresh. Authentic. Delicious.</p>
  </header>

  <section class="menu">
    <h2>Our Menu</h2>
    <div class="menu-item">
      <h3>Cheese Pizza</h3>
      <p>$8 - Classic and cheesy goodness</p>
    </div>
    <div class="menu-item">
      <h3>Pasta Alfredo</h3>
      <p>$10 - Creamy sauce with herbs</p>
    </div>
    <div class="menu-item">
      <h3>Chocolate Lava Cake</h3>
      <p>$6 - Rich and gooey dessert</p>
    </div>
  </section>

  <section class="about">
    <h2>About Us</h2>
    <p>Welcome to Delicious Bites! We serve mouth-watering dishes made with love and fresh ingredients.</p>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <p>📞 Call us: 123-456-7890</p>
    <p>📍 Visit us: 456 Foodie Street, Flavor Town</p>
  </section>

  <footer>
    <p>&copy; 2025 Delicious Bites. All rights reserved.</p>
  </footer>
</body>

#css code
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #fff8f0;
    color: #333;
  }
  
  header {
    background-color: #e63946;
    color: white;
    text-align: center;
    padding: 30px 20px;
  }
  
  header h1 {
    margin: 0;
    font-size: 36px;
  }
  
  section {
    padding: 30px 20px;
    max-width: 800px;
    margin: auto;
  }
  
  .menu-item {
    background-color: #f1f1f1;
    padding: 15px;
    border-radius: 10px;
    margin-bottom: 15px;
  }
  
  .about, .contact {
    background-color: #ffe8d6;
    border-radius: 10px;
    margin-top: 30px;
  }
  
  footer {
    text-align: center;
    padding: 15px;
    background-color: #222;
    color: white;
  }
  
</html>
