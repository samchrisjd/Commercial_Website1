# Ex02 Commercial Website
## Date:28.03.2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
# index.html
```python
<!DOCTYPE html>
<html>
<head>
<title>MAGESH SHOP</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>

<div class="header-container">
<img src="img/logo.jpg" alt="Logo" class="logo">
<h1>Power Tools Store</h1>
</div>

<nav>
<a href="#home">Home</a>
<a href="#products">Products</a>
<a href="#contact">Contact</a>
</nav>

</header>

<!-- Home Section -->

<section id="home">
<h2>Welcome to Power Tools Shop</h2>
<p>Best Professional Power Tools at Affordable Prices</p>
</section>

<!-- Products Section -->

<section id="products">

<h2>Our Products</h2>

<div class="products">

<div class="product">
<img src="img/cord.jpg" alt="Cordless Drill">
<h3>Cordless Drill</h3>
<p>₹4500</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/angle.jpg" alt="Angle Grinder">
<h3>Angle Grinder</h3>
<p>₹3500</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/saw.jpg" alt="Circular Saw">
<h3>Circular Saw</h3>
<p>₹6200</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/impact.jpg" alt="Impact Driver">
<h3>Impact Driver</h3>
<p>₹5000</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/hammer.jpg" alt="Power Hammer">
<h3>Power Hammer</h3>
<p>₹7200</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/sander.jpg" alt="Electric Sander">
<h3>Electric Sander</h3>
<p>₹2800</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/chain saw.jpg" alt="Jigsaw Machine">
<h3>Jigsaw Machine</h3>
<p>₹4100</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/gun.jpg" alt="Heat Gun">
<h3>Heat Gun</h3>
<p>₹1900</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/bench.jpg" alt="Bench Grinder">
<h3>Bench Grinder</h3>
<p>₹5500</p>
<button>Buy Now</button>
</div>

<div class="product">
<img src="img/planer.jpg" alt="Electric Planer">
<h3>Electric Planer</h3>
<p>₹4300</p>
<button>Buy Now</button>
</div>

</div>

</section>

<!-- Contact Section -->

<section id="contact">

<div class="contact-box">
<h2>Contact Us</h2>

<form>

<label>Full Name</label>
<input type="text" required>

<label>Email</label>
<input type="email" required>

<label>Phone</label>
<input type="tel" required>

<label>Message</label>
<textarea rows="4"></textarea>

<button type="submit">Send Message</button>

</form>

</div>

</section>

<!-- Footer -->

<footer>
<p>© 2026 Power Tools Store</p>
</footer>

</body>
</html>
```
# style.css
```python
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#f5f5f5;
}

/* Header */

header{
background:#111;
color:white;
padding:20px;
text-align:center;
}

.header-container{
display:flex;
align-items:center;
justify-content:center;
gap:15px;
}

.logo{
width:60px;
height:60px;
object-fit:cover;
border-radius:50%;
}

/* Navigation */

nav{
margin-top:10px;
}

nav a{
color:white;
text-decoration:none;
margin:0 15px;
font-weight:bold;
}

nav a:hover{
color:orange;
}

/* Sections */

section{
padding:50px 20px;
text-align:center;
}

/* Products Layout using Flexbox */

.products{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:25px;
margin-top:30px;
}

/* Product Card */

.product{
background:white;
width:220px;
padding:15px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.15);
display:flex;
flex-direction:column;
align-items:center;
transition:0.3s;
}

.product:hover{
transform:translateY(-5px);
}

/* Product Images */

.product img{
width:180px;
height:140px;
object-fit:cover;
border-radius:6px;
margin-bottom:10px;
}

/* Buttons */

button{
background:#2563eb;
color:white;
border:none;
padding:8px 15px;
border-radius:5px;
cursor:pointer;
}

button:hover{
background:#1e40af;
}

/* Contact */

.contact-box{
background:white;
width:350px;
margin:auto;
padding:25px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.15);
}

.contact-box label{
display:block;
margin-top:10px;
text-align:left;
}

.contact-box input,
.contact-box textarea{
width:100%;
padding:8px;
margin-top:5px;
border:1px solid #ccc;
border-radius:5px;
}

.contact-box button{
margin-top:15px;
width:100%;
}

/* Footer */

footer{
background:#111;
color:white;
text-align:center;
padding:15px;
margin-top:40px;
}
```
## OUTPUT

![alt text](Screenshot_18-3-2026_134650_.jpeg)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
