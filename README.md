# Birdwatching
Website for birdwatching.

Birdwatching.html

(HTML CODE)

<!DOCTYPE html>
 <html lang="en">
 <meta charset="utf-8">
 <head>
 	<title>Birdwatching</title>
 	<link rel="stylesheet" type="text/css" href="style.css"/>
 <body>
 <header class="page-header">
 	<h1>BIRDWATCHING</h1>
 	<img src="images/dove.png">
 	 <nav>
 		<ul>
 			<li><a href="#">HOME</a></li>
 		    <li><a href="#">GET STARTED</a></li>
 		    <li><a href="#">PHOTOS</a></li>
 		    <li><a href="#">GEAR</a></li>
 		    <li><a href="#">FORUM</a></li>
 	    </ul>
 	</nav>
 </header>

 <main>
 	<article>
 		<h2>WELCOME</h2>
 		<p>Welcome to our fake birdwatching site. If this were a real site, it would be the ideal place to come to learn more about birdwatching, whether you are a beginner looking to learn how to get into birding, or an expert wanting to share ideas, tips, and photos with other like-minded people.</p>

 		<p>So don't waste time! Get what you need, then turn off that computer and get out into the great outdoors!</p>
 	</article>

 	<aside>
 		<h3>FAVOURITE PHOTOS</h3>

 		<div class="row">
 			<div class="column">
 				<img src="images/favorite-1.jpg" width="120" height="120" alt="Bird sitting on a flower">
 			</div></li>

 			<div class="column">
 				<img src="images/favorite-2.jpg" width="120" height="120" alt="A picture of a peacock">
 			</div>

 			<div class="row">
 				<div class="column">
 					<img src="images/favorite-3.jpg" width="120" height="120" alt="A picture of a white bird">
 				</div>

 			<div class="column">
 				<img src="images/favorite-4.jpg" width="120" height="120" alt="A picture of a stork">
 			</div>
 		</div>
 	</aside>
 </main>

 <footer>
 	<p>©Copyright 2020 by Dzastina. All rights reserved.</p>
 </footer>
 </body>
 </html>
 
 (STYLE.CSS TO GO WITH IT)
 
 html, body {
  margin: 0;
  padding: 0;
  background-color:  #879986;
}

html {
  font-size: 10px
  background-color: green;
}

body {
  width: 70%
  min-width: 800px;
  margin: 0 auto;

}

h1, h2 {
  font-family: 'Cinzel Decorative', cursive;
  color: black;
}

h3 {
  font-family: 'Roboto', sans-serif;
  color: black;
  text-align: center;
}

p, input, il {
  font-family: 'Roboto', sans-serif;
  color: black;
}

h1 {
  font-size: 4rem;
  text-align: center;
  text-shadow: 2px 2px 10px black;
}

h2 {
  font-size: 3rem;
  text-align: center;
}

h3 {
  font-size: 2.2rem
}

p, il {
  font-size: 1.6rem;
  line-height: 1.5;}

header {
  margin-bottom: 10px;
  display: flex;
  flex-flow: row wrap;
}

body > * {
  padding: 1%;
}

main, header, nav, article, aside, footer, section {
  background-color: #2ac726;
}

h1 {
  flex: 5;
  text-transform: uppercase;
  height: 100px;
}

header img {
  display: block;
  height: 100px;
  padding-top: 15px;
}

nav{
  height: 50px;
  flex: 100%;
  display: flex;
  background-color: #1aee14;
}

nav ul {
  padding: 0;
  list-style-type: none;
  flex: 2;
  display: flex;
  background-color: #1aee14;
}

nav li {
  display: inline;
  text-align: center;
  flex: 1;
  background-color: #1aee14;
}

nav a, nav span {
  display: inline-block;
  font-size: 2rem;
  height: 1rem;
  line-height: 0.7;
  text-transform: uppercase;
  text-decoration: none;
  color: black;
  background-color: #1aee14;

}

main {
  display: flex;
  background-color: #879986;
}

article, section {
  flex: 4;
  background-color: #1aee14;
}

aside {
  background-color: #1aee14;
}

aside {
  flex: 1;
  margin-left: 10px;
  padding: 2%
}

aside a {
  display: block;
  float: right;
  width: 85%
}

aside img {
  max-width: 100%
}

* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 50%
  padding: 5px;
}

.row::after {
  content:
  display: table;
  clear: both;
}

footer {
  margin-top: 10px;
}
