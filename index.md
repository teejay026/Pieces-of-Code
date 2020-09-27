<!DOCTYPE html>

<html>
	<head>
	<style type="text/css">
	html{
	background: linear-gradient(35deg, pink, black);
	background-repeat: no-repeat;
	background-size: cover;
	width: 100%;
	height: 100%;
	}
	h1 {
	color: #FF007F;
	position: relative;
	text-shadow: 5px 5px 5px pink;
	font-size: 70px;
	text-align: center;
	}
	
	p {
	color: white;
	font-size: 40px;
	font-style: italic;
	position: relative;
	text-align: center;
	}
	
	body {
	margin: auto;
	}
	
	#left {
	float: left;
	width: 20%;
	text-align: center;
	background-color: black;
	border-radius: 50%;
	}
	
	#right {
	float: right;
	width: 20%;
	text-align: center;
	background-color: black;
	border-radius: 50%;
	}
	
	section, aside {
	position: auto;
	padding: 1px 1px 1px 1px
	height: 30px;
	width: 30px;
	left: 30px;
	right: 30px;
	}
	
	section:hover {
	transform: scale(1.1);
	}
	
	aside:hover {
	transform: scale(1.1);
	}
	
	div {
	width: 50%;
	height: 50px;
	margin: 50px auto;
	}
	
	#top {
	background-color: pink;
	transform: skewX(30deg);
	}
	
</style>
</head>
<title> Sticker Space </title>
<body>
<h1>Welcome to Sticker Space</h1>
<p>Sticker Space is your source of cool sticker designs. 
Get browsing and find something awesome!</p>
	<section id="left">
		<h2><a href="https://www.redbubble.com/shop/?iaCode=all-stickers&query=space" target=_blank>Space Stickers</a></h2>
	</section>
	<aside id="right">
		<h2><a href="https://www.redbubble.com/shop/?iaCode=all-stickers&query=cat&ref=search_box" target=_blank>Cat Stickers</a></h2>
	</aside>
	<div id="top"></div>
</body>
</html>