# Ex.07 Restaurant Website
## Date: 05.10.2025

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
home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Oops! I am Hungry Restaurant</title>
  <link rel="stylesheet" href="style1.css">
</head>
<body>
  <header>
    <h1>Oops! I am Hungry</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="banner">
    <img src="banner.webp" alt="Delicious Food Banner">
  </section>

  <section class="content">
    <h2>Welcome!</h2>
    <p>Discover the best food in town, made with passion and fresh ingredients.</p>
  </section>

  <footer>
    <p>&copy; 2025. Designed by AMAL TONY CHARLES.A</p>
  </footer>
</body>
</html>
menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Our Restaurant</title>
  <link rel="stylesheet" href="style2.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <div class="menu-item">
      <img src="pizza.webp" alt="Pizza">
      <h3>Pizza</h3>
      <p>The sauce is typically made with tomatoes, olives, capers, and anchovies.</p>
    </div>

    <div class="menu-item">
      <img src="burger.webp" alt="Burger">
      <h3>Quinoa Burger</h3>
      <p>The burger patty is made from quinoa, topped with cheese, caramelized onions, and fries.</p>
    </div>

    <div class="menu-item">
      <img src="penne.webp" alt="Pasta">
      <h3>Penne Bolognese</h3>
      <p>Classic Italian sauce made with ground meat, tomatoes, carrots, and celery.</p>
    </div>

    <div class="menu-item">
      <img src="white.webp" alt="White Sauce Pasta">
      <h3>White Sauce Pasta</h3>
      <p>Pasta tossed in creamy sauce made from milk, butter, and flour with veggies.</p>
    </div>

    <div class="menu-item">
      <img src="barotta.webp" alt="Barota">
      <h3>Barota </h3>
      <p>🔥 “Hot Barota, Spicy Salna, Happy Hearts!”
🥘 “Barota – Taste That Twirls!” </p>
    </div>

    <div class="menu-item">
      <img src="meatball.webp" alt="Meatballs">
      <h3>Spaghetti with Meatballs</h3>
      <p>Spaghetti topped with tomato-based sauce and meatballs, served with parmesan.</p>
    </div>

   

   

    <div class="menu-item">
      <img src="biriyani - Copy.webp" alt="Biryani">
      <h3>Biryani</h3>
      <p>Served with chicken pieces, boiled egg, and raita on the side.</p>
    </div>

    <div class="menu-item">
      <img src="juice - Copy.webp" alt="Juice">
      <h3>Fruit Juice</h3>
      <p>Refreshing drink with essential minerals but low in fiber.</p>
    </div>

    <div class="menu-item">
      <img src="ice - Copy.webp" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>Vanilla, chocolate, and strawberry scoops available.</p>
    </div>

    
  </section>

  <footer>
    <p>&copy; AMAL TONY CHARLES.A</p>
  </footer>
</body>
</html>
administration.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Our Restaurant</title>
  <link rel="stylesheet" href="style3.css">
</head>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <div class="admin-card">
      <img src="lal.jpg" alt="Admin 1">
      <h3>Lal Ridhisian</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="surya.png" alt="Admin 2">
      <h3>Surya</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="pp.jpg" alt="Admin 3">
      <h3>Piruthvi </h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="prag.png" alt="Admin 4">
      <h3>Prahatheeswaran</h3>
      <p>Cashier</p>
    </div>
    <div class="admin-card">
      <img src="saravana.jpg" alt="Admin 5">
      <h3>Saravanan</h3>
      <p>Inventory Manager</p>
    </div>
    <div class="admin-card">
      <img src="vikramm.jpg" alt="Admin 6">
      <h3>Vikram</h3>
      <p>Customer Service</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by AMAL TONY CHARLES A</p>
  </footer>
</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Our Restaurant</title>
  <link rel="stylesheet" href="style4.css">
</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>Get in Touch</h2>
    <p>📍 <strong>Address:</strong> Saveetha College, Sriperumbuthur , Chennai</p>
    <p>📞 <strong>Phone:</strong> 8870369975</p>
    <p>✉ <strong>Email:</strong> amaltonycharles@gmail.com</p>
  </section>

  <footer>
    <p>&copy; 2025. Designed by AMAL TONY CHARLES</p>
  </footer>
</body>
</html>
style.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #e6b184;
  color: #1e1111;
}

header {
  background-color: #481a1a;
  color: rgba(255, 255, 255, 0.9);
  padding: 20px;
  text-align: center;
}

nav a {
  color: #ddd;
  margin: 0 20px;
  text-decoration: none;
}

.banner img {
  width: 1750px;
  height: 500px;
}

.content {
  padding: 40px;
  text-align: center;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
style2.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fff3e0;
  color: #1e1111;
}

header {
  background-color: #3e1f1f;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: #f0dcdc;
  margin: 0 20px;
  text-decoration: none;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 25px;
  padding: 40px;
}

.menu-item {
  background-color: #f8d7c4;
  border: 3px solid #3e1f1f;
  padding: 15px;
  border-radius: 20px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
style3.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
}

header {
  background-color: #2e2e2e;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: #ddd;
  margin: 0 20px;
  text-decoration: none;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #d9d9d9;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 2px solid #333;
}

.admin-card img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

style4.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fff;
  color: #111;
}

header {
  background-color: #004d40;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: #e0f7fa;
  margin: 0 20px;
  text-decoration: none;
}

.contact-info {
  padding: 50px;
  text-align: center;
  line-height: 1.8;
  background-color: #f1f1f1;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}


```


## OUTPUT:
![alt text](<Screenshot 2025-10-15 132150.png>)
![alt text](<Screenshot 2025-10-15 132133.png>)
![alt text](<Screenshot 2025-10-15 132205.png>)
![alt text](<Screenshot 2025-10-15 132219.png>)##RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
