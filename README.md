# Ex.06 Restaurant Website
## Date:
18.12.2025
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
  <title>Amadora</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #872d2d;
      color: #fff700;
    }
    header {
      background: #782b2b;
      text-align: center;
      padding: 20px;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    nav {
      background: #ce1111;
      text-align: center;
      padding: 10px 0;
    }
    nav a {
      color: #ffd500;
      text-decoration: none;
      margin: 0 20px;
      font-weight: bold;
    }
    nav a:hover {
      color: #ffcc00;
    }
    .banner {
      background: url('Screenshot 2025-09-29 231228.png') no-repeat center/cover;
      color: rgb(255, 217, 0);
      padding: 60px 20px;
      text-align: center;
    }
    .banner h2 {
      font-size: 30px;
      margin-bottom: 10px;
    }
    .cards {
      display: flex;
      justify-content: space-around;
      margin: 20px;
      gap: 15px;
    }
    .card {
      background: #000000;
      padding: 15px;
      border-radius: 10px;
      width: 30%;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    .card img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
    }
    section {
      padding: 20px;
    }
    .footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
    .footer span {
      color: orange;
      font-weight: bold;
    }
  </style>
</head>

<body>

<header>
  <h1>🥗Amadora🥗</h1>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#menu">Menu</a>
  <a href="#admin">Administration</a>
  <a href="#contact">Contact Us</a>
</nav>

<!-- HOME SECTION -->
<section id="home">
  <div class="banner">
    <h2>30% Off This Weekend For You</h2>
    <p>Enjoy delicious meals with special discounts only at Amadora!</p>
    <p>Visit us this weekend and savor the flavors.</p>
    <p><b>Offer valid from Friday to Sunday.</b></p>
  </div>

  <div class="cards">
    <div class="card">
      <h3>Our New Menu</h3>
      <img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\top-view-chicken-salad-with-vegetables-dark-floor-diet-salad-health.jpg">
      <p>Check out our fresh and tasty new dishes for this season.</p>
    </div>

    <div class="card">
      <h3>Book a Table</h3>
      <img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\istockphoto-1018141890-612x612.jpg">
      <p>Reserve your table easily and enjoy dining with us.</p>
    </div>

    <div class="card">
      <h3>Opening Hours</h3>
      <img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\a-clock-made-of-leftover-food-scraps-free-photo.jpg">
      <p>Mon–Fri: 10am - 10pm<br>Sat: 11am - 1am<br>Sun: 2pm - 12am</p>
    </div>
  </div>
</section>

<!-- MENU SECTION -->
<section id="menu" style="text-align:center; background-color:#7b1e1e;">

<h2 style="color:yellow; font-size:36px; letter-spacing:3px;">OUR MENU</h2>

<table style="margin:auto;" cellpadding="20">

<tr>
<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\grill chicken.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">Grill Chicken</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹300</p>
</div>
</td>

<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\veg salad.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">Veg Salad</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹150</p>
</div>
</td>

<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\pizza.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">Chicken Pizza</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹450</p>
</div>
</td>
</tr>

<tr>
<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\pasta.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">White Sauce Pasta</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹200</p>
</div>
</td>

<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\cheesburger.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">Cheeseburger</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹100</p>
</div>
</td>

<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\fish curry.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">Fish Curry</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹150</p>
</div>
</td>
</tr>

<tr>
<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\chicken briyani.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">Chicken Biryani</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹250</p>
</div>
</td>

<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\curry.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">Prawn Fry</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹200</p>
</div>
</td>

<td>
<div style="background:black; width:230px; height:360px; border-radius:25px; padding:15px;">
<img src="C:\Users\acer\Exp6_WebsiteRestaurant\restaurantproject\restaurant_app\templates\paneer.jpg"
style="width:200px; height:200px; object-fit:cover; border-radius:20px;">
<p style="color:yellow; font-size:22px; font-weight:bold;">Tandoori Paneer</p>
<p style="color:white; font-size:20px; font-weight:bold;">₹180</p>
</div>
</td>
</tr>

</table>
</section>

<!-- ADMIN SECTION -->
<section id="admin">
  <h2>Administration</h2>
  <ul>
    <li>Venkatramani – Manager</li>
    <li>Aydin – Chef</li>
    <li>Bharat – Assistant Chef</li>
    <li>Saahithya – Waitress</li>
    <li>Tharun – Waiter</li>
    <li>Vijay Mallya – Cashier</li>
  </ul>
</section>

<!-- CONTACT SECTION -->
<section id="contact">
  <h2>Contact Us</h2>
  <p><b>Address:</b> Perumal Kovil 1st st, Kotturpuram, Chennai, India</p>
  <p><b>Phone:</b> +91 7305897444</p>
  <p><b>Email:</b> info@amadora.com</p>
</section>

<div class="footer">
  Designed and Developed by <span>R.Venkatramani 25010118</span>
</div>

</body>
</html>
```

## OUTPUT:
![alt text](image.png)
![alt text](<Screenshot 2025-12-17 231109.png>)
![alt text](<Screenshot 2025-12-17 231150.png>)
![alt text](<Screenshot 2025-12-17 231225.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
