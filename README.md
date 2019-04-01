# Dasmoto-s-Arts-Crafts-Project
Web Design Project from Codecademy, Dasmoto's Arts &amp; Crafts Project

[Project5.zip](https://github.com/AxiomEXE/Dasmoto-s-Arts-Crafts-Project/files/3031345/Project5.zip)

Original Spec Design:https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/dasmotos-arts_redline.jpg
![dasmotos-arts_redline](https://user-images.githubusercontent.com/42499071/55360105-74597b80-54a1-11e9-991f-9ea318fed967.jpg)


Index HTML

```markdown

 <!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Dasmoto's Arts</title>
	<link rel="stylesheet" style="text/css" href="./style.css">
</head>
<body>
	<h1>Dasmoto's Arts & Crafts</h1>
	<div class="brush">
		<h2>Brushes</h6>
		<img src="https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/hacksaw.jpeg" alt="brushes">
		<h3>Hacksaw Brushes</h3>
		<p>Made of the highest quality oak, Hacksaw brshes are known for their weight and ability to hold paint in large amounts. Available in different sizes. <a href="price">Starting at $3.00 / brush.</a></p>
	</div>
	<div class="frame">
		<h2>Frames</h6>
		<img src="https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/frames.jpeg" alt="frames">
		<h3>Art Frames (assorted)</h3>
		<p>Assorted frames made of different material, including MDF, birchwood, and PDE. Select frames can be sanded and painted according to your needs. <a href="price">Starting at $2.00 / frame.</a></p>
	</div>
	<div class="paint">
		<h2>Paint</h6>
		<img src="https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/finnish.jpeg" alt="paint">
		<h3>Clean Finnish Paint</h3>
		<p>Imported paint from Finland. Over 256 colors available in-store, varying in quantity (1 oz. to 8 oz.). Clean Finnish paint microbinds to canvas, increasing the finish and longevity of any artwork. <a href="price">Starting at $5.00 / tube.</a></p>
	</div>
</body>
</html>
 
```

Style CSS

```markdown

body {
	font-family: Helvetica;
}

h1 {
	background-image: url("https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-2/pattern.jpeg");
	font-size: 100px;
	font-weight: bold;
	color: khaki;
	text-align: center;
}

.brush h2 {
	background-color: mediumspringgreen;
	font-size: 32px;
	font-weight: bold;
	color: white;
}

.brush a {
	font-weight: bold;
	color: blue;
	text-decoration: none;
}

.frame h2 {
	background-color: lightcoral;
	font-size: 32px;
	font-weight: bold;
	color: white;
}

.frame a {
	font-weight: bold;
	color: blue;
	text-decoration: none;
}

.paint h2 {
	background-color: skyblue;
	font-size: 32px;
	font-weight: bold;
	color: white;
}

.paint a {
	font-weight: bold;
	color: blue;
	text-decoration: none;
}

```
