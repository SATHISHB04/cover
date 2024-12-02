# Ex.06 Book Front Cover Page Design
## Date:01.12.2024

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
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
        }
        .cover {
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            position: relative;
            overflow: hidden;
            background: linear-gradient(135deg, #1e3c72, #2a5298); /* Blue gradient */
        }
        .cover::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: repeating-linear-gradient(
                45deg,
                rgba(255, 255, 255, 0.1) 0,
                rgba(255, 255, 255, 0.1) 10px,
                transparent 10px,
                transparent 20px
            );
            z-index: 0;
        }
        .top-banner {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 30%;
            background: linear-gradient(to right, rgba(0, 0, 0, 0.7), transparent);
            clip-path: polygon(0 0, 100% 0, 100% 60%, 0% 100%);
            z-index: 1;
        }
        .title {
            text-align: center;
            color: #ffffff;
            font-size: 2.5rem;
            margin: 1rem 0;
            font-weight: bold;
            z-index: 2;
            position: relative;
        }
        .new-quote {
            text-align: center;
            color: #e0f7fa;
            font-size: 1.5rem;
            margin-bottom: 1.5rem;
            font-style: italic;
            font-weight: 500;
            z-index: 2;
            position: relative;
        }
        .subtitle {
            text-align: center;
            font-size: 1.2rem;
            color: #f1f1f1;
            margin-bottom: 1.5rem;
            z-index: 2;
            position: relative;
        }
        .edition {
            text-align: center;
            font-size: 1.2rem;
            color: #b3e5fc;
            font-weight: bold;
            margin-bottom: 1rem;
            z-index: 2;
            position: relative;
        }
        .author {
            text-align: center;
            font-size: 1.5rem;
            font-weight: bold;
            margin-top: 2rem;
            color: #ffffff;
            z-index: 2;
            position: relative;
        }
        .photo {
            border: 5px solid #ffffff;
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-top: 1rem;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            z-index: 2;
            position: relative;
        }
        .bottom-banner {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 20%;
            background: linear-gradient(to right, transparent, rgba(0, 0, 0, 0.7));
            clip-path: polygon(0 0, 100% 40%, 100% 100%, 0% 100%);
            z-index: 1;
        }
    </style>
</head>
<body>
    <div class="cover">
        <div class="top-banner"></div>
        <div class="edition">Third Edition</div>
        <div class="title">Response Web Design in HTML and CSS</div>
        <div class="new-quote">"Designing the future, one responsive site at a time."</div>
        <div class="subtitle">Develop future-proof websites using the latest technologies</div>
        <img src="web.png" alt="Author Photo" class="photo">
        <div class="author">Sathish B</div>
        <div class="bottom-banner"></div>
    </div>
</body>
</html>
 ```

## OUTPUT:
![alt text](<sasi/myapp/static/Screenshot (43).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
