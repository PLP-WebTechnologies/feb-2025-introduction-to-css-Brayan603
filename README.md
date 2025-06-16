# Introduction to CSS
SS is a style sheet language used to describe the presentation and layout of HTML elements. It helps you control the look and feel of your website—colors, fonts, spacing, and layout—separately from the content1.



## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking External CSS -->
</head>
<body>

    <h1 class="title">Welcome to My Styled Page</h1>

    <p id="description">This page is styled using external CSS with different selectors.</p>

    <img src="image.jpg" alt="Sample Image" class="styled-image">

    <div class="box">
        <p>This is a styled box with padding, margin, and a border.</p>
    </div>

</body>
</html>


/* Applying styles using different selectors */

/* 1. Class Selector */
.title {
    font-family: 'Arial', sans-serif;
    color: #3498db;
    text-align: center;
}

/* 2. ID Selector */
#description {
    font-size: 18px;
    color: #555;
    text-align: center;
    margin-bottom: 20px;
}

/* 3. Element Selector */
body {
    background-color: #f4f4f4;
    font-family: 'Verdana', sans-serif;
    margin: 0;
    padding: 20px;
}

/* Styling an Image */
.styled-image {
    width: 300px;
    display: block;
    margin: 20px auto;
    border: 3px solid #333;
    border-radius: 10px;
}

/* Adding Margin, Padding & Borders */
.box {
    background-color: white;
    border: 2px solid #000;
    padding: 20px;
    margin: 30px auto;
    width: 60%;
    text-align: center;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

