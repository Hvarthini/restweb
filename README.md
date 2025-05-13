# Ex.07 Restaurant Website
## Date: 13.05.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Spice & Herb Bistro</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fffaf0;
      color: #333;
    }
    header {
      background-color: #a83232;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background-color: #f8c291;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .section img {
      width: 300px;
      height: 200px;
      object-fit: cover;
      margin: 10px;
      border-radius: 10px;
    }
    .menu-items {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    .menu-item {
      width: 250px;
      margin: 15px;
      padding: 15px;
      background: #fceae8;
      border-radius: 10px;
    }
    footer {
      background-color: #a83232;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Spice & Herb Bistro</h1>
    <p>Flavors of India with a European twist</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>Welcome to Spice & Herb Bistro, where Indian spices meet European elegance. We blend traditional flavors with a modern twist to delight your palate.</p>
    <img src="C:\WEB\inti.jpeg" alt="Restaurant Interior">
  </section>

  <section id="menu" class="section">
    <h2>Our Menu</h2>
    <div class="menu-items">
      <div class="menu-item">
        <h3>Spicy Butter Chicken Pasta</h3>
        <img src="C:\WEB\bc.jpeg" alt="Butter Chicken Pasta">
        <p>Fusion of creamy butter chicken with penne pasta.</p>
      </div>
      <div class="menu-item">
        <h3>Herb Paneer Tikka</h3>
        <img src="C:\WEB\paneer tikka.jpeg" alt="Paneer Tikka">
        <p>Grilled paneer marinated in Mediterranean herbs.</p>
      </div>
    </div>
  </section>

  <section id="gallery" class="section">
    <h2>Gallery</h2>
    <img src="C:\WEB\d1.jpeg" alt="Dish 1">
    <img src="C:\WEB\d2.jpeg" alt="Dish 2">
    <img src="C:\WEB\amb.jpeg" alt="Ambience">
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> 123 Food Street, saveetha City, America</p>
    <p><strong>Phone:</strong> ‪+91 1234567890‬</p>
    <p><strong>Email:</strong>harsha@gmail.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Spice & Herb Bistro. All rights reserved.</p>
  </footer>

</body>
</html>
```
## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
