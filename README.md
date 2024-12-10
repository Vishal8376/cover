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
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(10, 10, 10);
            margin-left: auto;
            margin-right: auto;
            padding:5px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(my\ image.jpg);
        }

        .insight{
            color:rgb(13, 6, 6) ;

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: rgb(76, 137, 29);
            display: inline;
            position: relative;
            color: rgb(32, 174, 176);
            top: 220px;

            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: top;
            top: 10px;
            color: rgb(245, 89, 72);
        }

        .id{
            width: 410px;
            position: relative;
            top: 210px;

        }

        .pub{
            font-size: large;
            position: relative;
            top: 170px;
            left: 300px;
        }
        .ed{
            color: rgb(133, 34, 118);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 110px;

        }
        .subtitle{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 70px;
            color: rgb(245, 89, 72);;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="EXPERT INSIGHT">
                
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(255, 65, 65);">
            </div>
            <div class="booktitle">
                <h1>BASICS OF WEB DEVELOPMENT USING HTML AND CSS</h1>
            </div>
            <div class="subtitle">
            GUIDE FOR BEGINNERS
            </div>
            <div class="id">
                <hr style="color:rgb(10, 10, 10);">
            </div>
            <div class="author">
                <p><b>Vishal S</b></p>
            </div>
            <div class="pub">
                CSE
            </div>
            <div class="ed">
                <b>Exclusive Edition</b>
            </div>
        </div>
    </body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-10 205333.png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
