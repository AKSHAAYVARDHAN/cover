# Ex.06 Book Front Cover Page Design
## Date:24-12-2024

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
<html>

<head>
    <title>Front Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-color: #111;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            position: relative;
            background-image: url(Plane.jpg);
            background-size: cover;
            background-position: center;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.6);
        }

        .booktitle {
            color: rgb(240, 252, 255);
            font-family: 'Arial', sans-serif;
            font-size: 25px;
            text-align: center;
            position: absolute;
            top: 0px;
            width: 90%;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .subtitle {
            text-align: center;
            font-size: 22px;
            color: white;
            position: absolute;
            top: 80px;
            width: 90%;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.5);
        }

        .mypic {
            position: absolute;
            top: 400px;
            left: 35px;
            width: 60px;
            height: 100px;
            background-size: cover;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.6);
        }

        .author {
            text-align: left;
            color: rgb(127, 207, 244);
            font-family: 'Georgia', serif;
            font-size: 16px;
            position: absolute;
            top: 520px;
            width: 100%;
            text-shadow: 1px 1px 4px rgba(116, 211, 243, 0.5);
        }

        .id {
            width: 100%;
            position: absolute;
            top: 520px;
        }

        .end {
            color: azure;
            font-size: 20px;
            font-family: 'Verdana', sans-serif;
            text-align: center;
            position: absolute;
            bottom: 20px;
            width: 90%;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.5);
        }

        hr {
            border: none;
            border-top: 1px solid blanchedalmond;
            margin-top: 50px;
            margin-bottom: 50px;
        }
    </style>
</head>

<body>
    <div class="bookpage">

        <div class="booktitle">
            <h1><font color="CYAN">THE LOST PLANE</font></h1>
        </div>

        <div class="mypic">
            <img src="profilepic.jpg" width="110" height="120">
        </div>

        <div class="id">
            <hr style="color: blanchedalmond">
        </div>

        <div class="author">
            <p><b>Akshaay Vardhan</b></p>
        </div>

        <div class="end">
            <b>THE DISAPPEARANCE OF THE PLANE</b>
        </div>
    </div>
</body>

</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-24 140135.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
