
<!DOCTYPE html>
<html>
<head>
	<title>polypage</title>
	<link rel="stylesheet" type="text/css" href="css/bootstrap.css">
	<script type="text/javascript" src="animation.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link href="css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="css/b4_sidebar.css">
    <link rel="stylesheet" href="css/navbar-top-fixed.css">
    <link rel="stylesheet" href="css/custom.css">
    <link rel="stylesheet" href="css/signin.css">
<style>
body {margin:0;font-family:Arial}

.topnav {
  overflow: hidden;
  background-color: green;
}
 #img{
     	width: 100%;
     	
     }


.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.active {
  background-color: red;
  color: white;
}

.topnav .icon {
  display: none;
}

.dropdown {
    float: left;
    overflow: hidden;
}

.dropdown .dropbtn {
    font-size: 17px;    
    border: none;
    outline: none;
    color: white;
    padding: 14px 16px;
    background-color: inherit;
    font-family: inherit;
    margin: 0;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: teal;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    float: none;
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.topnav a:hover, .dropdown:hover .dropbtn {
  background-color: #555;
  color: white;
}

.dropdown-content a:hover {
    background-color: #ddd;
    color: black;
}

.dropdown:hover .dropdown-content {
    display: block;
}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child), .dropdown .dropbtn {
    display: none;
  }
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
  .topnav.responsive .dropdown {float: none;}
  .topnav.responsive .dropdown-content {position: relative;}
  .topnav.responsive .dropdown .dropbtn {
    display: block;
    width: 100%;
    text-align: left;
  }
}
.jumbotron li{
	text-decoration: none;
	display: inline;
	margin: 8px;
}
.jumbotron li a:hover{
	background: purple;
}
.cell a{
	margin:8px;
}
.jumbotron{
	background: #ccc;
}
.row a{
  float: center;
  margin-left: 20px;
}
</style>
</head>
<body>

<div class="topnav" id="myTopnav">
  <a href="#home" class="active">Home</a>
  <a href="#news">Manager</a>
  <a href="#contact">Patient room</a>
  <a href="#contact">pregnant</a>
  <a href="#contact">Contact us</a> 
  <a href="#about">About</a>
  <a href="javascript:void(0);" style="font-size:15px;" class="icon" onclick="myFunction()">&#9776;</a>
</div>


<div style="padding-left:16px">
	
	 <div class="row">

	  	<div class="well well-sm"  style="background:teal">
		<h2 class="text-center" style="color:white">POLY CLINIC HOSPITAL
			<a href="workers/login.php" class="btn btn-info">Login</a>
      <a href="workers/register.php" class="btn btn-info">Register</a>
		</h2>
	     </div>
	    <div class="image">
			<img src="image/pg1.jpg" id="img">
		</div>
	 
	 </div>
</div>

<div class="jumbotron">
	<div class="row">

	    <div class="col-sm-3 col-md-6 col-lg-4 cell">
	     <div class="col-lg-4">Contact us</div>
	     <br>
	         <li><span class="glyphicon glyphicon-earphone" style="font-size:20px; color:green">07064562237</span></li>
	         <li><span class="glyphicon glyphicon-earphone" style="font-size:20px; color:green">N0Address Inepentent layout Enugu</span></li>  
	    </div>

	    <p>
	    <p>
	    <p>
	    	<p>
	    <div class="col-sm-3 col-md-6 col-lg-4 cell" style="feont-size:2px solid red; color:green">
	      <p class="text-center">coppyright @ Miracle 2018 project.</p>
	      <ol>
		     
		    
	      </ol>
	   
	  </div>
  

</body>
</html>
<script>
function myFunction() {
    var x = document.getElementById("myTopnav");
    if (x.className === "topnav") {
        x.className += " responsive";
    } else {
        x.className = "topnav";
    }
}
</script>
