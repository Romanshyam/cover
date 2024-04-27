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
'''
<!DOCTYPE html>
<html>

<head>
    <title>ARTIFICAL INTELLIGENCE AND DATA SCIENCE</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:cyan;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(tim.jpeg);
            background-size: cover;
        }
            
        
        .insight{
            color:skyblue (250, 255, 240);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 81, 0);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(255, 192, 194);
            font-family: 'Courier New', Courier, monospace;
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
            color:yellow;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:white;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:aqua(255, 240, 251);
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
                SCOFT
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>ARTIFICAL INTELLIGENCE AND DATA SCIENCE</h1></div>
            <div class="subtitle">
                 book on FL studio workings
            </div>
            <div class="subtitle">
                AI is a mirror, reflecting not only our intellect, but our value and fears"
            </div>

            <div class="mypic">
                <img src="pro.jpg" width="80" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>SHYAM KUMAR E</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>


</html>



## OUTPUT:
![Screenshot 2024-04-27 083033](https://github.com/Romanshyam/cover/assets/123962992/50759261-ffbd-4c09-8ca0-af62e51df6ff)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
