<img width="1882" height="1048" alt="image" src="https://github.com/user-attachments/assets/d0a73be0-1cff-4290-89d2-27199f4c35a5" />
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Library Management System</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#f4f4f4;
}

header{
background:#1e3a8a;
color:white;
padding:15px;
display:flex;
justify-content:space-between;
align-items:center;
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
background:linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
url('https://images.unsplash.com/photo-1521587760476-6c12a4b040da');
background-size:cover;
color:white;
text-align:center;
}

.hero h1{
font-size:50px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
margin-bottom:20px;
}

.search-box{
display:flex;
width:60%;
}

.search-box input{
flex:1;
padding:15px;
border:none;
outline:none;
}

.search-box button{
padding:15px 25px;
background:#2563eb;
color:white;
border:none;
cursor:pointer;
}

.features{
padding:50px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
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
color:#1e3a8a;
}

footer{
background:#1e3a8a;
color:white;
text-align:center;
padding:15px;
margin-top:20px;
}
</style>
</head>

<body>

<header>
<h2>Library Management System</h2>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Books</a></li>
<li><a href="#">Materials</a></li>
<li><a href="#">Login</a></li>
<li><a href="#">Register</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav>
</header>

<section class="hero">
<h1>Welcome To Library Portal</h1>
<p>Search, Borrow and Manage Books Easily</p>

<div class="search-box">
<input type="text" placeholder="Search Books">
<button>Search</button>
</div>
</section>

<section class="features">

<div class="card">
<h3>Book Catalog</h3>
<p>Search and view all available books.</p>
</div>

<div class="card">
<h3>Borrow History</h3>
<p>Track issued books and return dates.</p>
</div>

<div class="card">
<h3>Study Materials</h3>
<p>Download year-wise and semester-wise materials.</p>
</div>

<div class="card">
<h3>Fine Management</h3>
<p>Check pending fines and due dates.</p>
</div>

<div class="card">
<h3>Admin Dashboard</h3>
<p>Manage books, students and materials.</p>
</div>

<div class="card">
<h3>User Profile</h3>
<p>Manage account information and borrowing records.</p>
</div>

</section>

<footer>
<p>© 2026 Library Management System</p>
</footer>

</body>
</html>      
