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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FWAD Book Cover</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #f4f4f4;
        }

        .cover {
            width: 400px;
            height: 600px;
            background: linear-gradient(135deg, #e81ac2, #42a5f5, #f66478);
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            align-items: center;
            text-align: center;
            padding: 20px;
            color: white;
        }

        .cover-header {
            margin-top: 20px;
        }

        .title {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.2em;
            font-weight: 300;
            margin-bottom: 20px;
        }

        .graphic {
            width: 80%;
            max-width: 250px;
            margin: 30px 0;
        }

        .cover-footer {
            margin-bottom: 20px;
        }

        .author {
            font-size: 1.2em;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .tagline {
            font-size: 1em;
            font-style: italic;
            color: #e0f7fa;
        }

        .line {
            width: 80%;
            height: 2px;
            background: #e0f7fa;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="cover">
        <div class="cover-header">
            <div class="title"></div>
            <div class="subtitle">WALK INTO THE SHADOW</div>
            <div class="subtitle">THE MYSTERIOUS STORY</div>
        </div>

        <div class="graphic">
            <img src="C:\Users\Naveen kumar S\cover\book.png" alt="Code Illustration" style="width: 110%; border-radius: 2px;">
        </div>
        <div class="line"></div>
        <div class="cover-footer">
            <div class="author">Naveen kumar S</div>
            <div class="tagline">"story"</div>
        </div>
    </div>
</body>
</html>
'''

## OUTPUT:
![alt text](<Screenshot 2024-12-09 115042.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
