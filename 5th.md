<img width="1913" height="952" alt="image" src="https://github.com/user-attachments/assets/78395ba9-94df-458b-b738-68d073ebd5db" /><img width="1913" height="952" alt="image" src="https://github.com/user-attachments/assets/921462c3-cc42-451b-8e05-1d9a6cc7ccb2" />

Daily Report
Number of Tickets Booked
Revenue Generated
Monthly Report
Total Bookings
Total Revenue
Flight Occupancy Report
Seats Filled
Seats Available
Cancellation Report
Cancelled Tickets
Refund Amounts

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Flight Reservation System</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#f4f6f9;
}

header{
background:#003566;
color:white;
padding:15px 50px;
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
margin-left:25px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
height:90vh;
background:linear-gradient(rgba(0,0,0,0.5),
rgba(0,0,0,0.5)),
url('https://images.unsplash.com/photo-1436491865332-7a61a109cc05');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
color:white;
text-align:center;
}

.hero h1{
font-size:55px;
margin-bottom:15px;
}

.hero p{
font-size:22px;
margin-bottom:30px;
}

.search-box{
background:white;
padding:20px;
border-radius:10px;
width:85%;
display:grid;
grid-template-columns:repeat(5,1fr);
gap:10px;
}

.search-box input,
.search-box select,
.search-box button{
padding:12px;
border:1px solid #ccc;
border-radius:5px;
}

.search-box button{
background:#0077b6;
color:white;
border:none;
cursor:pointer;
font-weight:bold;
}

.search-box button:hover{
background:#023e8a;
}

.features{
padding:60px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
text-align:center;
}

.card h3{
color:#003566;
margin-bottom:10px;
}

.card p{
color:#555;
}

footer{
background:#003566;
color:white;
text-align:center;
padding:15px;
}
</style>

</head>
<body>

<header>
<div class="logo">✈ SkyFly Airlines</div>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Search Flight</a></li>
<li><a href="#">My Ticket</a></li>
<li><a href="#">Booking Status</a></li>
<li><a href="#">Login</a></li>
<li><a href="#">Register</a></li>
</ul>
</nav>
</header>

<section class="hero">

<h1>Book Flights Online</h1>

<p>Search, Compare and Reserve Airline Tickets Instantly</p>

<div class="search-box">

<input type="text" placeholder="From">

<input type="text" placeholder="To">

<input type="date">

<select>
<option>Economy</option>
<option>Premium Economy</option>
<option>Business</option>
<option>First Class</option>
</select>

<button>Search Flights</button>

</div>

</section>

<section class="features">

<div class="card">
<h3>Search Flights</h3>
<p>Find flights by destination, date and class.</p>
</div>

<div class="card">
<h3>Seat Selection</h3>
<p>Choose your preferred seat before booking.</p>
</div>

<div class="card">
<h3>Secure Payment</h3>
<p>Pay safely using integrated payment gateway.</p>
</div>

<div class="card">
<h3>E-Ticket</h3>
<p>Receive instant e-ticket confirmation.</p>
</div>

<div class="card">
<h3>Booking History</h3>
<p>View all previous reservations anytime.</p>
</div>

<div class="card">
<h3>Print Ticket</h3>
<p>Download and print your ticket easily.</p>
</div>

</section>

<footer>
<p>© 2026 Flight Reservation System | All Rights Reserved</p>
</footer>

</body>
</html>
```
