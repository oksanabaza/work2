<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
	<style>
		*{
			margin: 0;
			padding: 0;
		}
		.clearfix:before,
		.clearfix:after{
			content: '';
			display: block;
			clear: both;
			float: none;


		}
		.Header{
			position: relative;
			width: 1000px;
			margin: auto;


		}

		.Navigation{
			position: absolute;
			right: 0;
			top: 50%;
			transform: translate(0,-50%);


		}
		.Logo{
			display: block;
		}

		.Logo_wrapper{
			display: block;
			float: left;
		}
		.Navigation_link{
			margin: 10px;
			padding: 5px 10px;
			text-decoration: none;
			background-color: red;
			color: black;
			border-radius: 6px;
			font-family: sans-serif;
		
		}
	</style>
</head>
<body>
	<header class="Header clearfix" >
		<a class="Logo_wrapper" href="#">
			<img src="https://placehold.it/100x50" alt="Logo" class="Logo" width="100" height="50">
		</a>
		<nav class="Navigation clearfix" >
			<a class="Navigation_link" href="#">Menu</a>
			<a class="Navigation_link" href="#">Menu</a>
			<a class="Navigation_link" href="#">Menu</a>
			<a class="Navigation_link" href="#">Menu</a>
		</nav>
	</header>
</body>
