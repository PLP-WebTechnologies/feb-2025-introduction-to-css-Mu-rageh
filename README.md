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

#HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Styling</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header id="main-header">
    <h1>Welcome to My Styled Page</h1>
  </header>

  <div class="content-section">
    <img src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Cityscape" class="styled-image">
    <p class="main-paragraph">
      This is a paragraph with some styled text. We're using CSS to make it look nicer.
      We're also demonstrating margins, padding, and borders.
    </p>
    <p class="main-paragraph">
      Another paragraph with a different style. This paragraph shows the usage of a different font.
    </p>

    <ul id="styled-list">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ul>
  </div>

</body>
</html>
#CSS
/* style.css */

body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

#main-header {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 1em 0;
}

.content-section {
  width: 80%;
  margin: 20px auto;
  padding: 20px;
  background-color: #fff;
  border: 1px solid #ddd;
  box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
}

.styled-image {
  width: 100%;
  max-width: 600px;
  display: block;
  margin: 0 auto 20px;
  border-radius: 8px;
}

.main-paragraph {
  font-size: 1.1em;
  line-height: 1.6;
  margin-bottom: 15px;
  padding: 10px;
  border: 1px solid #eee;
}

.main-paragraph:last-child {
  font-family: 'Georgia', serif; /* Different font */
}

#styled-list {
    list-style-type: square;
    padding-left: 20px;
}

Happy Coding! 💻✨
