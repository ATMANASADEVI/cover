# Ex.06 Book Front Cover Page Design
## Date:1/12/2024
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
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage {
                width: 400px;
                height: 600px;
                color: black;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url(back.jpg);
                background-size: cover;
                position: relative;
            }

            .insight {
                color: black;
            }

            .hrstyle {
                width: 100px;
                
            }

            .booktitle {
                font-family: 'Courier New', Courier, monospace;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;
            }

            .subtitle {
                font-family: Tahoma;
                font-size: large;
                position: relative;
                top: 40px;
            }

            .id {
                width: 400px;
                position: relative;
                top:350px;
            }

            .mypic {
                position: absolute;
                bottom:60px;
                right: 5px;
                width: 100px;
                left:320px;
                height: 100px;
                background-size: cover;
            }

            .author {
                position: absolute;
                bottom: 10px;
                left: 30px;
                font-family: Georgia;
                font-size: medium;
                text-align: right;
            }

            .pub {
                font-size: medium;
                position: absolute;
                bottom: 25px;
                right: 30px;
            }

            .ed {
                color: black;
                font-size: medium;
                font-family: Verdana;
                position: absolute;
                bottom: 55px;
                left: 30px;
            }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Introduction to Machine Learning</h1>
            </div>
            <div class="subtitle">
                This is How Machines will change day by day in our daily lives
            </div>
            <div class="id">
                <hr style="color: blue;">
            </div>
            <div class="mypic">
                <img src="Myphoto.jpg" width="100" height="100" alt="">
            </div>
            <div class="author">
                <p><b>A.T Manasa Devi</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>


## OUTPUT:
![alt text](<Screenshot (59).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
