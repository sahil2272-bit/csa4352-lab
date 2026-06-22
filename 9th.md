<img width="1915" height="1073" alt="image" src="https://github.com/user-attachments/assets/2f8738e2-c74f-449e-807c-785df6cc53c8" />

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TechSavvy Electronics Store</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#f5f5f5;
}

header{
background:#0f172a;
color:white;
padding:15px 50px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-size:30px;
font-weight:bold;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:25px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
height:90vh;
background:linear-gradient(rgba(0,0,0,.5),
rgba(0,0,0,.5)),
url('https://images.unsplash.com/photo-1519389950473-47ba0277781c?w=1600');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
color:white;
}

.hero h1{
font-size:55px;
margin-bottom:15px;
}

.hero p{
font-size:22px;
margin-bottom:25px;
}

.search-box{
background:white;
padding:20px;
border-radius:10px;
display:flex;
gap:10px;
width:80%;
max-width:900px;
}

.search-box input{
flex:1;
padding:12px;
border:1px solid #ccc;
border-radius:5px;
}

.search-box button{
padding:12px 20px;
background:#2563eb;
color:white;
border:none;
border-radius:5px;
cursor:pointer;
}

.categories{
padding:60px;
}

.categories h2{
text-align:center;
margin-bottom:30px;
}

.category-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,.1);
text-align:center;
}

.card h3{
margin-bottom:10px;
color:#2563eb;
}

.products{
padding:60px;
background:#eef2ff;
}

.products h2{
text-align:center;
margin-bottom:30px;
}

.product-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.product-card{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 0 10px rgba(0,0,0,.1);
}

.product-card img{
width:100%;
height:220px;
object-fit:cover;
}

.product-info{
padding:15px;
text-align:center;
}

.product-info h3{
margin-bottom:10px;
}

.product-info p{
margin-bottom:10px;
}

.product-info button{
padding:10px 15px;
background:#2563eb;
color:white;
border:none;
cursor:pointer;
border-radius:5px;
}

footer{
background:#0f172a;
color:white;
text-align:center;
padding:15px;
}

</style>
</head>

<body>

<header>

<div class="logo">💻 TechSavvy</div>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Products</a></li>
<li><a href="#">Cart</a></li>
<li><a href="#">Orders</a></li>
<li><a href="#">Login</a></li>
<li><a href="#">Register</a></li>
</ul>
</nav>

</header>

<section class="hero">

<h1>Latest Electronic Gadgets</h1>

<p>Shop Smartphones, Laptops, Tablets & Accessories</p>

<div class="search-box">
<input type="text" placeholder="Search Products">
<button>Search</button>
</div>

</section>

<section class="categories">

<h2>Shop By Category</h2>

<div class="category-grid">

<div class="card">
<h3>📱 Smartphones</h3>
<p>Android & iPhone Devices</p>
</div>

<div class="card">
<h3>💻 Laptops</h3>
<p>Gaming & Professional Laptops</p>
</div>

<div class="card">
<h3>⌚ Smart Watches</h3>
<p>Fitness & Lifestyle Wearables</p>
</div>

<div class="card">
<h3>🎧 Accessories</h3>
<p>Headphones, Chargers & More</p>
</div>

</div>

</section>

<section class="products">

<h2>Featured Products</h2>

<div class="product-grid">

<div class="product-card">
<img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9">
<div class="product-info">
<h3>iPhone 16</h3>
<p>₹79,999</p>
<button>Add To Cart</button>
</div>
</div>

<div class="product-card">
<img src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853">
<div class="product-info">
<h3>Gaming Laptop</h3>
<p>₹89,999</p>
<button>Add To Cart</button>
</div>
</div>

<div class="product-card">
<img src="https://images.unsplash.com/photo-1546868871-7041f2a55e12">
<div class="product-info">
<h3>Smart Watch</h3>
<p>₹9,999</p>
<button>Add To Cart</button>
</div>
</div>

</div>

</section>

<footer>
<p>© 2026 TechSavvy Electronics Store | All Rights Reserved</p>
</footer>

</body>
</html>
```
