# Ex.06 Book Front Cover Page Design
## Date:22/5/2025

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            background-color: #7ebac7;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
        }
        
        .cover {
            width: 700px;
            height: 1000px;
            border: 15px solid #0c0b13;
            background-color: #138af2;
            display: block;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 30px;
            background-image: url("vector-jan-2021-34_generated.jpg");
            background-size: cover;
        }
        
        .title {
            font-size: 60px;
            font-weight: bold;
            margin-top: 100px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            color: #1993b9;
        }
        
        .subtitle {
            margin-top: 5px;
            font-size: 40px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            color: rgb(188, 35, 172);
        }
        
        .author {
            font-size: 30px;
            font-style: italic;
            color: #929c34;
            margin-top: 450px;
            margin-bottom: 5px;
        }
        
        .bottom-text {
            margin-top: 20px;
            font-size: 30px;
            color: #519b79
        }
        
        .img {
            margin-top: 20px;
            margin-left: 150px;
            width: 80px;
            height: 80px;
        }
        
        footer {
            font-size: 1px;
        }
    </style>
</head>

<body>
    <div class="cover">
        <header>

            <div class="title">PYTHON PROGRAMMING</div>
            <hr color="white">
            <div class="subtitle"> FOR BEGINNERS</div>
            <hr color="white" width="300px">
        </header>
        <div class="img"><img src="python logo.png" width="400px" height="500px"></div>
        <footer>
            <div class="author">
                <hr width="35px">~By guido van rossum </div>
            <hr width="700px" color="white">
            <div class="bottom-text">Published by official PYTHON <br><br>REVISED EDITION</div>
        </footer>
    </div>
</body>

</html>

```


## OUTPUT:
![392528173-cdb31ba6-925e-4db8-8933-4d4a7fc22370](https://github.com/user-attachments/assets/ddfc941d-2a4a-451e-925f-ef7cb1764a95)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
