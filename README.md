# Introduction to CSS

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
  <title>Safe Space Kenya</title>
  <link rel="stylesheet" href="styles.css"> <!-- External CSS link -->
</head>
<body>
  <header>
    <h1>SAFE SPACE</h1>
  </header>

  <section>
    <p class="intro">This is a brief introduction to my styled webpage.</p>
    <p>Enjoy exploring various features enhanced by CSS.</p>
  </section>

  <button id="cta-button">Click Me!</button>
</body>
</html>
/* 1. Element Selector */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f8fb;
  color: #333;
  line-height: 1.6;
  margin: 20px;
}

/* 2. Class Selector */
.intro {
  font-size: 1.2rem;
  font-weight: bold;
  color: #2a6592;
}

/* 3. ID Selector */
#cta-button {
  background-color: #2a6592;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

#cta-button:hover {
  background-color: #1f4a70;
}

