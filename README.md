# EXPERIMENT-04
# <p align="center"> COMMERCIAL WEBSITE - VERTICAL FARM </P>

## AIM: 
To create a commercial website using HTML & CSS.
     
## ALGORITHM:

### STEP 1:
Create an HTML file with the necessary structure and add a CSS file for styling.
### STEP 2:
Define a container div for the entire webpage.
### STEP 3:
Create a navigation bar with a logo and navigation links.
### STEP 4:
Add buttons for "Start free trial" and "Account".
### STEP 5:
Create a content section with text, images, and buttons.
### STEP 6:
Include information boxes with accompanying circles.
### STEP 7:
Apply appropriate classes and styles to the elements.
### STEP 8:
Import Google Fonts in the CSS file.
### STEP 9:
Reset default margin, padding, and box-sizing.
### STEP 10:
Style the navigation bar, heading, and navigation links.
### STEP 11:
Apply styles to the buttons and arrow icon.
### STEP 12:
Set up the row and column layout for the content section.
### STEP 13:
Style the text, images, and information boxes.
### STEP 14:
Save and link the CSS file in the HTML document.
### STEP 15:
Test the webpage to ensure proper display and functionality.

## PROGRAM:

### index.html
```
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8" />

<meta name="viewport" content="width=device-width, initial-scale=1.0" />
 
<link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet"/>

<link rel="stylesheet" href="assests/css/style.css">

<title>Home</title>

</head>

<body>

<!-- Navigation bar -->

<div class="container">

<nav>

<div class="heading">

<img src="assests/img/logo.jpg" alt="Profile-Pic">

<h4>Vertical Farm</h4>

</div>

<ul class="nav-links">

<a href="#solutions">Solutions</a>

<a href="#Department">Department <i class="arrow myarrow"> </i></a>

<a href="#Farming Method">Farming Method</a>

<a href="#company">Company</a>

<a href="#about">About</a>

<button class="button">Start free trial</button>

<button class="button1">Account</button>


</ul>

</nav>

<!-- Body of the webiste -->

<div class="row">

<div class="col">

<p>Fresh, Substainable,</p>

<p>Plant <b>Grown Vertically</b></p>

<p>in <span class="high"><strong>Urban Areas</strong></span></p>

<br>

<br>

<h4>Our Vertical farming startup Substainable, locally grown produce to urban areas. With oru innovation technology, we're revolutionizing the way we grew and consume fresh food.</h4>

<div class="in-img">

<img src="assests/img/side.jpg" alt="side-Pic_2">
 
</div>

<br>

<br>

<button class="button2">Start Now &#x2197</button>

<button class="button3">HOW IT WORKS?</button>

<img src="assests/img/mini.jpg" alt="side-Pic_1">

<div>

<p class="box"><strong>Choose the right crops</strong><br>Select the best crop for your vertical farming</p>

<div class="circle">1</div>

</div>

<div>

<p class="box1"><strong>Set up your grow system</strong><br>install and set up your vertical farming</p>

<div class="circle1">2</div>

</div>

<div>

<p class="box3"><strong>Monitor your crops</strong><br>Regurarly monitor your crops</p>

<div class="circle3">3</div>

</div>

</div>

</div>

</div>

</body>

</html>

```

### style.css
```css
@import
url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;1,500;1,600;1,700;1,800;1,900&display=swap');

*{

margin: 0px; padding: 0px;
box-sizing: border-box;

}

.container{ width: 100%; height:100vh;
background-color: #101012;
 
}

nav{

display: flex;

justify-content: space-around; align-items: center;
font-family: "Montserrat", sans-serif;

}

.heading { color: white;
margin-left: -200px; float: left;
letter-spacing: 5px; font-size: 6px;
}

.heading h4{ font-size: 2.5em;
margin: .7em 0 1em 0; display: inline-block; padding-top: 18px;
}

.heading img{

max-width: 40px; float: left;
margin: 18px 10px 10px 140px;

}

.nav-links { width: 60%; overflow: auto;
}

.nav-links a { float: left; padding: 12px; color: white;
text-decoration: none; font-size: 13px;
 
width: 15%; text-align: left;
margin-left: -12px;

}

a:hover {

color: #BBC19D;

}

.button { float: right; color: #ffffff;
border-radius: 30px; border: 0.1px solid #ffffff; padding: 10px 20px;
background: rgb(0, 0, 0); font-size: 0.7em;
cursor: pointer; position: absolute; width: 110px;
left: 1180px; top: 20px;
}

.button1 { float: right;
color: #000000; border-radius: 30px;
border: 0.5px solid #000000; padding: 10px 15px; position: absolute;
width: 80px; top: 20px; left: 1300px;
background: #E3F3C4; font-size: 0.7em; cursor: pointer;
}
 
.button2{ float: left;
color: #000000; border-radius: 30px;
border: 0.5px solid #000000; padding: 10px 15px; position: absolute;
width: 100px; left: 80px;
background: #F0FFA0; font-size: 0.7em; cursor: pointer;
}

.button3{ float: right; color: #ffffff;
border-radius: 30px; border: 0.1px solid #ffffff; padding: 10px 20px;
background: rgb(0, 0, 0); font-size: 0.7em;
cursor: pointer; position: absolute; width: 140px;
left: 190px;

}

.arrow {

border: solid rgb(255, 255, 255);

border-width: 0 1px 1px 0; display: inline-block; padding: 1.5px;
position: relative; left: 4px;
}

.myarrow {
 
transform: rotate(45deg);

-webkit-transform: rotate(45deg);

}

.row{ display: flex; color: #ffffff; height: 70%;
align-items: center;

}

.col{

flex-basis: 50%;

}

p{

font-size: 50px; padding-left: 80px; font-family: "Poppins";
}

.high {

background-color: #F0FFA0; color: #000000;
padding: 2px; border-radius: 4px;
}

.col h4{

font-family: Verdana, Geneva, Tahoma, sans-serif; font-size: 15px;
height: 20%; padding-left: 80px; font-weight: 30;
}

.col img{

max-width: 100px; float: left; position: absolute; width: 150px;
 
left: 350px; top: 475px;
}

.in-img img{

max-width: 30%; float: left; position: absolute; width: 100%;
left: 880px; top: 150px;
}

.box{

background-color: #E4F1C3; color: #000000;
border: 0.1px solid #ffffff; padding: 10px 70px;
font-size: 0.7em; border-radius: 10px; position: absolute; width: 400px;
top: 600px;

margin-left: 5%;

}

.circle {

border-radius: 50%; width: 34px;
height: 34px; padding: 8px; background: #fff;
border: 1px solid #000; color: #000;
text-align: center;

font: 1em Arial, sans-serif; position: absolute;
left: 100px;
 
top: 610px;

}

.box1{

background-color: #F1FEA2; color: #000000;
border: 0.1px solid #ffffff; padding: 10px 70px;
font-size: 0.7em; border-radius: 10px; position: absolute; width: 365px;
top: 600px;

margin-left: 31.2%;

}

.circle1 {

border-radius: 50%; width: 34px;
height: 34px; padding: 8px;
background: #000000; border: 1px solid #000; color: #ffffff;
text-align: center;

font: 1em Arial, sans-serif; position: absolute;
left: 500px; top: 610px;
}

.box3{

background-color: #FEFEFE; color: #000000;
border: 0.1px solid #ffffff; padding: 10px 70px;
font-size: 0.7em; border-radius: 10px;
 
position: absolute; width: 365px;
top: 600px;

margin-left: 55.1%;

}

.circle3 {

border-radius: 50%; width: 34px;
height: 34px; padding: 8px;
background: #000000; border: 1px solid #000; color: #fffefe;
text-align: center;

font: 1em Arial, sans-serif; position: absolute;
left: 860px; top: 610px;
}

``` 
  
## OUTPUT:

![image](https://github.com/Sugan2002/vertical-farm/assets/77089743/adcc4f28-dc25-4c16-91ed-c6fa6b1fcdb9)

## RESULT:

   Thus, a commercial vertical is developed successfully using HTML & CSS.
