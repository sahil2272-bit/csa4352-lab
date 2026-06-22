<img width="1918" height="1077" alt="image" src="https://github.com/user-attachments/assets/3641c31a-e912-4691-ac4c-26c778a68bad" />

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Railway Reservation System</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f4f4f4;
}

header{
background:#003049;
padding:15px;
display:flex;
justify-content:space-between;
align-items:center;
color:white;
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
height:90vh;
background:linear-gradient(rgba(0,0,0,.6),
rgba(0,0,0,.6)),
url('train.jpg');
background-size:cover;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
color:white;
}

.hero h1{
font-size:50px;
margin-bottom:20px;
}

.search-box{
background:white;
padding:20px;
border-radius:10px;
display:grid;
grid-template-columns:repeat(5,1fr);
gap:10px;
width:85%;
}

.search-box input,
.search-box select,
.search-box button{
padding:12px;
}

.search-box button{
background:#003049;
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
padding:20px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,.1);
text-align:center;
}

footer{
background:#003049;
color:white;
text-align:center;
padding:15px;
}

</style>
</head>

<body>

<header>

<h2>Railway Reservation System</h2>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Train Search</a></li>
<li><a href="#">PNR Status</a></li>
<li><a href="#">Login</a></li>
<li><a href="#">Register</a></li>
</ul>
</nav>

</header>

<section class="hero">

<h1>Book Train Tickets Online</h1>

<div class="search-box">

<input type="text" placeholder="From Station">

<input type="text" placeholder="To Station">

<input type="date">

<select>
<option>Select Class</option>
<option>Sleeper (SL)</option>
<option>3A</option>
<option>2A</option>
<option>1A</option>
<option>Chair Car (CC)</option>
</select>

<button>Search Train</button>

</div>

</section>

<section class="features">

<div class="card">
<h3>Train Search</h3>
<p>Find trains by route and date.</p>
</div>

<div class="card">
<h3>Live Seat Availability</h3>
<p>Check available seats instantly.</p>
</div>

<div class="card">
<h3>PNR Status</h3>
<p>Track your booking status.</p>
</div>

<div class="card">
<h3>Ticket Cancellation</h3>
<p>Easy refund and cancellation.</p>
</div>

</section>

<footer>

<p>© 2026 Railway Reservation System</p>

</footer>

</body>Functional Requirements
Passenger/User Module
Authentication
User Registration
Login
Logout
Forgot Password
Change Password
Train Search
Search Train by Source Station
Destination Station
Journey Date
Class Type
Train Number
Reservation
View Train List
Check Seat Availability
View Route (Via Stations)
Enter Passenger Details
Select Class (SL, 3A, 2A, 1A, CC)
Book Ticket
Payment
Online Payment
Offline Payment
Payment Receipt
PNR Services
Generate PNR Number
Check PNR Status
Confirmed
RAC
Waiting List
Ticket Management
View Ticket
Print Ticket
Download Ticket PDF
Booking History
Cancel Ticket
Refund Status
Admin Module
Train Management
Add Train
Update Train
Delete Train
Manage Train Routes
Schedule Management
Train Date Management
Departure Time
Arrival Time
Seat Availability
Fare Management
Zone Wise Fare
Class Wise Fare
Date Wise Fare
Passenger Management
View Users
Manage User Accounts
Ticket Management
View Reservations
Confirm Tickets
Manage RAC
Manage Waiting List
Refund Management
Approve Cancellation
Set Refund Percentage
Process Refunds
Reports
Daily Reservation Report
Monthly Reservation Report
Revenue Report
Refund Report
</html>
