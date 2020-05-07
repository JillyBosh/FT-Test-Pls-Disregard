<!DOCTYPE html>
<html lang="en">
<link rel="icon" href="favi2.png" type="image/x-icon">
	<meta charset="utf-8">
<head>
<body style="background-color:#FFFFFF;color:#89cff0;">
<!-- Project 2: h1 with the title of the page -->
<h1 style="background-color:#f0aa89;color:#FFFFFF;">Fairy Taco</h1> 

<style>
<!-- Project 2: Border -->
*, *:before, *:after {
  -moz-box-sizing: border-box; -webkit-box-sizing: border-box; box-sizing: border-box;
}

body { margin: 0; }

.columnsContainer, footer, header { position: relative; margin: .5em; }

.leftColumn, .rightColumn, footer, header {  border: 1px solid  #ccc; padding: 1.25em; }

.leftColumn { margin-bottom: .5em; }

.nav {
  list-style: none;
  margin-left: 0;
  margin-bottom: 0;
  padding-left: 0;
}

.nav > li,
.nav > li > a {
  display: inline-block;
  *display: inline;
  zoom: 1;
}

.inline-items {
  margin-top: 0;
}

.inline-items li {
  margin-left: 0;
  border-left: 1px solid black;
  padding-left: 10px;
  padding-right: 10px;
}

.inline-items li:first-child {
  margin-left: 0;
  border: none;
  padding-left: 0;
  padding-right: 10px;
}

.inline-items li:last-child {
  padding-right: 0;
}

/* MEDIA QUERIES */
@media screen and (min-width: 47.5em ) {
  .leftColumn { margin-right: 19.5em; }

	.rightColumn { position: absolute; top: 0; right: 0; width: 18.75em; }   
}
</style>
<script>
  window.console = window.console || function(t) {};
</script>
<script>
  if (document.location.search.match(/type=embed/gi)) {
    window.parent.postMessage("resize", "*");
  }
</script>
</head>
<body translate="no">
<html>



<body>

<header>
<nav>
<!-- Project 2: Relative Links -->
  	<b><a href="index.html">Home</a> &nbsp; 
	   <a href="About.html">About</a> &nbsp; 
	   <a href="Menu.html">Menu</a> &nbsp; 
	   <a href="contact.html">Contact</a>
	</b>

</nav>

</ul>
</nav>
</header>
<div class="columnsContainer">
<div class="leftColumn">
<h2>About</h2>
	 <dl>
	  <dt><strong>About Us</strong></dt>
	  <!-- Project 2: p with some sample text -->
	   <dd> <p style="color:#000000">At Fairy Taco we’re more than just a restaurant. Not only we provide delicious in-house plant-based tacos, for every order from our menu you’re also helping us plant trees and feed children around the world. Dogs are welcome to stay. We also provide delicious vegan treats for them as well. It’s a miracle. UPDATE: Mila decides to sell French Macarons in replace of tacos. </p> </dd>
	  <dt><strong>History</strong></dt>
	   <dd> <p style="color:#000000"> Mila (founder, investor, owner of Fairy Taco) has been plant-based for twenty years and wanted to share her avenue with more people of the plant-based lifestyle. She then established Fairy Taco in 2020 in the heart of Hawaii. Along with the food being in-house and sourced from local organic farms, every piece of equipment such as utensils, packaging, and décor at the restaurant are also eco-friendly. The restaurant’s focus isn’t just the plant-based tacos or the eco-friendly items, but also saving the world. Since adolescent Mila cared for people and trees. Mila and Fairy Taco teamed up with companies to assist in planting more trees and feeding children in need. Every sale made from our restaurant can plant thousands of trees and provide plant-based meals to children monthly. Reminder: Mila decides to sell French Macarons in replace of tacos.</p> </dd>
	 </dl>
	 
	 <figure>
  <center> <img src="aa.jpg" alt="Yum" style="width:30%" height="30%"> </center>
  <center><figcaption>Fig.2 - This is our latest goods</figcaption></center>
</figure>

</div>






<div class="RightColumn">
<h2>Order Online:</h2>
	<button class="button">Click Me!</button>
		</div>
</div>
</div>

<footer>
<hr>
<!-- Project 2: copyright message -->
	<small><i>Fairy Taco Hawaii. All rights reserved. &copy; Copyright 2020, Last Update: 5/7/2020</i></small>
</footer>
</main>
</body>
</html>
