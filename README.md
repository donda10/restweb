# Ex.07 Restaurant Website
## Date:
21-12-2024

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
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gourmet Delight</title>
    <link rel="stylesheet" href="rest1.css">
</head>
<body>
    <!-- Header -->
    <header class="header">
        <div class="banner">
            <h1>Gourmet Delight</h1>
            <p>Experience Fine Dining Like Never Before</p>
        </div>
        <nav class="nav-bar">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#administration">Administration</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Page -->
    <section id="home">
        <div class="content-wrapper">
            <h2>Our Story</h2>
            <p>
                Welcome to Gourmet Delight, where we combine culinary artistry with a luxurious atmosphere. 
                Our chefs use only the finest ingredients to create dishes that delight your taste buds and nourish your soul.
            </p>
        </div>
    </section>

    <!-- Menu Page -->
    <section id="menu">
        <div class="content-wrapper">
            <h2>Our Menu</h2>
            <div class="food-items">
                <div class="item">
                    <img src="istockphoto-157741539-612x612.jpg" alt="Pizza Margherita">
                    <p>Pizza Margherita</p>
                </div>
                <div class="item">
                    <img src="truffle-burger.jpg" alt="Gourmet Burger">
                    <p>Gourmet Burger</p>
                </div>
                <div class="item">
                    <img src="0Z4A4273-scaled.jpg" alt="Truffle Pasta">
                    <p>Truffle Pasta</p>
                </div>
                <div class="item">
                    <img src="gettyimages-1149200848-612x612.jpg" alt="Sashimi Platter">
                    <p>Sashimi Platter</p>
                </div>
                <div class="item">
                    <img src="lobster-tacos-ohead-pic.jpg" alt="Lobster Tacos">
                    <p>Lobster Tacos</p>
                </div>
                <div class="item">
                    <img src="gettyimages-1173079946-612x612.jpg" alt="Caesar Salad">
                    <p>Caesar Salad</p>
                </div>
                <div class="item">
                    <img src="Simply-Recipes-Sweet-Potato-Fries-METHOD-LEAD-seo-v2-f3f5d040c93d43ecaf15b2a5f0a9844e.jpg" alt="Sweet Potato Fries">
                    <p>Sweet Potato Fries</p>
                </div>
                <div class="item">
                    <img src="360_F_141426009_KQnjW9m7Y9YKdSdqJyGuYii9NoY5CDVN.jpg" alt="Filet Mignon">
                    <p>Filet Mignon</p>
                </div>
                <div class="item">
                    <img src="istockphoto-153479135-612x612.jpg" alt="French Onion Soup">
                    <p>French Onion Soup</p>
                </div>
                <div class="item">
                    <img src="thai-green-curry-recipe-p3-3217442-02-step-07-0574aa66709c467c8834f690d8dcc811.jpg" alt="Thai Green Curry">
                    <p>Thai Green Curry</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Administration Page -->
    <section id="administration">
        <div class="content-wrapper">
            <h2>Meet Our Team</h2>
            <div class="team">
                <div class="team-member">
                    <img src="MV5BMTU2MzYwNTczMV5BMl5BanBnXkFtZTgwMDIzMjk4MzI@.jpg" alt="Person 1">
                    <h3>Michael Scott</h3>
                    <p>Executive Manager</p>
                </div>
                <div class="team-member">
                    <img src="Screenshot (30).png" alt="Person 2">
                    <h3>Monica Geller</h3>
                    <p>Head Chef</p>
                </div>
                <div class="team-member">
                    <img src="MV5BZGIzOTRhY2ItYzdiOC00NTNlLWJmMTYtZGYzNWM2M2RiNjM3XkEyXkFqcGc@.jpg" alt="Person 3">
                    <h3>Jordan Peele</h3>
                    <p>Sous Chef</p>
                </div>
                <div class="team-member">
                    <img src="wp7544718.jpg" alt="Person 4">
                    <h3>Charles Boyle</h3>
                    <p>Senior Waiter</p>
                </div>
                <div class="team-member">
                    <img src="gettyimages-908311-612x612.jpg" alt="Person 5">
                    <h3>Rachel Green</h3>
                    <p>Receptionist</p>
                </div>
                <div class="team-member">
                    <img src="wp4758628.jpg" alt="Person 6">
                    <h3>Amy Santiago</h3>
                    <p>Maintenance</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Us Page -->
    <section id="contact">
        <div class="content-wrapper">
            <h2>Contact Us</h2>
            <p>Address: 123 Gourmet Avenue, Fine City</p>
            <p>Phone: +123-456-7890</p>
            <p>Email: contact@gourmetdelight.com</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 by Your Name. Crafted with elegance.</p>
    </footer>
</body>
</html>

CSS

/* General Styles */
body {
    font-family: 'Georgia', serif;
    margin: 0;
    padding: 0;
    color: #333;
    background-color: #f8f8f8;
    line-height: 1.6;
}

header {
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 10px;
    display: flex;
    justify-content: center;
    background: linear-gradient(90deg, #6b0f1a, #b91372);
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
    transition: background-color 0.3s;
}

nav ul li a:hover {
    background-color: #333;
    color: #fff;
}

/* Banner Section */
.banner {
    background-image: url('images/banner.jpg');
    background-size: cover;
    background-position: center;
    height: 250px;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-shadow: 2px 2px 5px black;
}

.banner h1 {
    font-size: 3em;
    margin: 0;
}

.banner p {
    font-size: 1.2em;
    margin: 10px 0;
}

/* Content Wrapper */
.content-wrapper {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
}

/* Food Items */
.food-items {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.food-items .item {
    background: #fff;
    border: 1px solid #ccc;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 15px;
    border-radius: 10px;
    transition: transform 0.3s;
}

.food-items .item:hover {
    transform: scale(1.05);
}

.food-items .item img {
    width: 100%;
    height: 120px;
    object-fit: cover;
    border-radius: 10px;
    margin-bottom: 10px;
}

.food-items .item p {
    margin: 0;
    font-size: 1em;
    font-weight: bold;
    color: #6b0f1a;
}

/* Team Section */
.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    gap: 30px;
}

.team-member {
    text-align: center;
    width: 150px;
}

.team-member img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
}

.team-member h3 {
    margin: 10px 0 5px;
    color: #6b0f1a;
}

.team-member p {
    color: #555;
    font-size: 0.9em;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}


```

## OUTPUT:
![alt text](<Screenshot (31).png>)
![alt text](<Screenshot (32).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
