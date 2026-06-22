<img width="1918" height="958" alt="image" src="https://github.com/user-attachments/assets/a327fd62-df7e-4fb5-bb33-aeecf3340d62" />

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cake Ordering System</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#fff5f7;
}

header{
background:#ff4d6d;
color:white;
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-size:28px;
font-weight:bold;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
height:80vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
background:linear-gradient(rgba(0,0,0,.4),rgba(0,0,0,.4)),
url('https://images.unsplash.com/photo-1578985545062-69928b1d9587');
background-size:cover;
background-position:center;
color:white;
text-align:center;
}

.hero h1{
font-size:55px;
margin-bottom:15px;
}

.hero p{
font-size:22px;
margin-bottom:20px;
}

.search-box{
background:white;
padding:20px;
border-radius:10px;
display:flex;
gap:10px;
width:80%;
}

.search-box input,
.search-box select{
padding:12px;
flex:1;
border:1px solid #ccc;
}

.search-box button{
padding:12px 20px;
background:#ff4d6d;
color:white;
border:none;
cursor:pointer;
}

.products{
padding:50px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 0 10px rgba(0,0,0,.1);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card-content{
padding:15px;
text-align:center;
}

.card-content h3{
margin-bottom:10px;
}

.card-content p{
margin-bottom:10px;
}

.card-content button{
padding:10px 15px;
background:#ff4d6d;
color:white;
border:none;
cursor:pointer;
}

footer{
background:#ff4d6d;
color:white;
text-align:center;
padding:15px;
}

</style>
</head>

<body>

<header>
<div class="logo">🎂 Cake Store</div>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Cakes</a></li>
<li><a href="#">Cart</a></li>
<li><a href="#">My Orders</a></li>
<li><a href="#">Login</a></li>
</ul>
</nav>
</header>

<section class="hero">

<h1>Order Delicious Cakes Online</h1>

<p>Fresh Cakes Delivered To Your Doorstep</p>

<div class="search-box">
<input type="text" placeholder="Search Cake">

<select>
<option>Category</option>
<option>Birthday</option>
<option>Wedding</option>
<option>Anniversary</option>
<option>Chocolate</option>
</select>

<button>Search</button>
</div>

</section>

<section class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1551024601-bec78aea704b">
<div class="card-content">
<h3>Chocolate Cake</h3>
<p>₹499</p>
<button>Add To Cart</button>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1464349095431-e9a21285b5f3">
<div class="card-content">
<h3>Birthday Cake</h3>
<p>₹699</p>
<button>Add To Cart</button>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1488477181946-6428a0291777">
<div class="card-content">
<h3>Strawberry Cake</h3>
<p>₹599</p>
<button>Add To Cart</button>
</div>
</div>

</section>

<footer>
<p>© 2026 Cake Ordering System | All Rights Reserved</p>
</footer>

</body>
</html>
```

