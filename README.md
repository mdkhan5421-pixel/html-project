# Task 01 [ Responsive Landing Page]
Author - Md Akram Khan


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Landing Page</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      line-height: 1.6;
    }
    header {
      background: #4f46e5;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 60px 20px;
      background: #f3f4f6;
      text-align: center;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    .hero p {
      max-width: 600px;
      margin-bottom: 30px;
    }
    .hero button {
      padding: 12px 25px;
      background: #4f46e5;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 40px 20px;
    }
    .feature {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      text-align: center;
    }
    footer {
      background: #111827;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h2>My Brand</h2>
    <nav>
      <a href="#">Home</a>
      <a href="#">Features</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Our Website</h1>
    <p>We provide the best solutions to grow your business online. Responsive, modern, and user-friendly design for all devices.</p>
    <button>Get Started</button>
  </section>

  <section class="features">
    <div class="feature">
      <h3>🚀 Fast</h3>
      <p>Optimized for speed and performance.</p>
    </div>
    <div class="feature">
      <h3>📱 Responsive</h3>
      <p>Looks perfect on mobile, tablet, and desktop.</p>
    </div>
    <div class="feature">
      <h3>🔒 Secure</h3>
      <p>Your data is safe with top-notch security.</p>
    </div>
  </section>

  <footer>
    <p>© 2025 My Brand. All rights reserved.</p>
  </footer>
</body>
</html>