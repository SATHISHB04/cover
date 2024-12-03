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
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .book-cover {
            position: relative;
            width: 600px;
            height: 800px;
            border-radius: 15px;
            border: 4px solid #ff3366;
            box-shadow: 0px 10px 40px rgba(0, 0, 0, 0.3);
            background: radial-gradient(circle, #ff9a8b, #ff3366);
            overflow: hidden;
        }

        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.3);
        }

        .content {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            box-sizing: border-box;
        }

        .title {
            font-size: 48px;
            font-weight: 900;
            color: #fffbf5;
            margin-bottom: 15px;
            text-shadow: 3px 3px 12px rgba(0, 0, 0, 0.6);
            letter-spacing: 2px;
        }

        .subtitle {
            font-size: 22px;
            font-weight: 300;
            color: #ffe0b2;
            margin-bottom: 40px;
            font-style: italic;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.4);
        }

        .bottom-section {
            position: absolute;
            bottom: 40px;
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
            padding: 0 30px;
            box-sizing: border-box;
        }

        .edition-author {
            text-align: left;
        }

        .edition {
            font-size: 20px;
            font-weight: bold;
            color: #fffbf5;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
        }

        .author {
            font-size: 20px;
            color: #fffbf5;
            font-weight: 500;
            margin-top: 5px;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
        }

        .profile-sec {
            text-align: center;
        }

        .author-photo {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #ff3366;
            margin-bottom: 10px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.3);
        }

        .institution {
            font-size: 22px;
            font-weight: bold;
            color: #fffbf5;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.5);
        }

        /* Decorative patterns */
        .pattern {
            position: absolute;
            width: 100%;
            height: 100%;
            background-image: url('https://www.transparenttextures.com/patterns/diagonal-stripes.png');
            opacity: 0.15;
            top: 0;
            left: 0;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="pattern"></div>
        <div class="overlay"></div>
        <div class="content">
            <h1 class="title">The Web Design Blueprint</h1>
            <p class="subtitle">Crafting Exceptional Digital Experiences with Design Excellence</p>
            <div class="bottom-section">
                <div class="edition-author">
                    <p class="edition">Tenth Edition</p>
                    <p class="author">SATHISH.B</p>
                </div>
                <div class="profile-sec">
                    <img src="photo.png" alt="Author's Photo" class="author-photo">
                    <p class="institution">SEC</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>

 ```

## OUTPUT:
![alt text](<Screenshot (57).png>)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
