# Ex.06 Book Front Cover Page Design
## Name:Yashaswini.S
## Register N0:212224220123
## Date:1-5-2025

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
            font-family: sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .book-cover {
            width: 400px;
            /* Adjust width as needed */
            background-image: url('your-image-url.jpg'); /* Replace with the actual URL of the image */
            background-size: cover;
            background-position: center;
            color: #333; /* Default text color */
            text-align: center;
            padding: 40px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            position: relative; /* For potential overlays */
        }

        .book-cover::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(255, 255, 255, 0.6); /* Optional overlay for better text readability */
            border-radius: 5px;
            z-index: 0;
        }

        .title {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
            position: relative;
            z-index: 1;
            color: #583d72; /* Example title color */
        }

        .subtitle {
            font-size: 1.2em;
            color: #777;
            position: relative;
            z-index: 1;
        }

        /* You can add more styles for author name, etc. */
    </style>
</head>
<body>

    <div class="book-cover">
        <h1 class="title">Pawprints on My Soul</h1>
        <p class="subtitle">Imprints of love, loyalty and unwavering connection</p>
        </div>

</body>
</html>
```

## OUTPUT:
![alt text](<bookcover ss.jpg>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
