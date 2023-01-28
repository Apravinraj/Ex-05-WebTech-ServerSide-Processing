# Design a Website for Server Side Processing

# AIM:

To design a website to perform mathematical calculations in server side.

# DESIGN STEPS:

##Step 1:
clone the repository from Github

##Step 2:
create Django Admin project

##Step 3:
create a new app

##Step 4:
create python programs for views and urls

##Step 5:
create a HTML file of forms.


# PROGRAM:

<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Rectangle</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:white;
}
.edge {
width: 1440px;
margin-left: auto;
margin-right: auto;
padding-top: 250px;
padding-left: 300px;
}
.box {
display:block;
width: 600px;
min-height: 400px;
font-size: 23px;
background-color:cyan;
}
.formelt{
color:blue;
text-align: center;
margin-top: 7px;
margin-bottom: 6px;
}
h1
{
color:blue;
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>Area of a Rectangle</h1>
<form method="POST">

<div class="formelt">
Length : <input type="text" name="length" value="l"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth : <input type="text" name="breadth" value="b"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area : <input type="text" name="area" value="area"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>

# OUTPUT:
![image](https://user-images.githubusercontent.com/118707879/215268923-430db1c7-b292-423c-9d86-14b92b7be1b4.png)

# RESULT:

The program is executed succesfully
