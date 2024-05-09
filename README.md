# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
<html>
<head>
    <title>CSE</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(back.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:black;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:crimson(255, 255, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:orange;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:cyan;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:black;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:greenyellow;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
            
            </div>
            <div class="hrstyle">
                <hr style="color:blueviolet">
            </div>
            <div class="booktitle">
                <h1>Communicating with Data</h1></div>
            <div class="subtitle">
                 books for beginners
            </div>
            <div class="subtitle">
                 Top seller of 2023
            </div>

            <div class="mypic">
                <img src="Photo.png" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:lightcoral">
            </div>
            <div class="author">
               <p><b>Harini.S (212223240048)</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION(LIMITED STOCK)</b>
            </div>
        </div>
        </body>
</html>
```

## OUTPUT:
![Screenshot 2024-05-09 084157](https://github.com/Hariniii21/cover/assets/147140423/ed44bd47-8c5e-4e00-8451-3af56f97cb83)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
