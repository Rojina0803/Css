


CSS Introduction
This project provides an introduction to CSS (Cascading Style Sheets) through a simple HTML document. It demonstrates the use of internal, external, and inline CSS styles to apply formatting to HTML elements.

Files
index.html: The main HTML file that incorporates CSS styles.
style.css: External CSS file containing additional styles.
HTML Structure
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <title>CSS Introduction</title>
  <!-- Internal CSS -->
  <style>
     h1, h2, p {
        color: black;
        font-size: larger;
        font-family: 'Courier New', Courier, monospace;
        font-weight: 100;
        font-style: italic;
     }
  </style>
  <!-- External CSS -->
  <link rel="stylesheet" href="/Css/style.css">
</head>
<body>
    <!-- Inline CSS -->
    <h1 style="color: red; font-size: 20px;">This is a heading.</h1>
    <h2 style="color: red; font-size: 20px;">This is a heading.</h2>
    <p>
        This is paragraph-1. Paragraphs are the building blocks of papers. 
        Many students define paragraphs in terms of length: a paragraph is a group of at least five sentences, a paragraph is half a page long, etc. 
        In reality, though, the unity and coherence of ideas among sentences is what constitutes a paragraph.
    </p>
</body>
</html>
CSS Styles
Internal CSS
Applies styles to h1, h2, and p elements.
Sets color to black, font size to larger, font family to Courier New, Courier, monospace, font weight to 100, and font style to italic.
External CSS
The external CSS file (style.css) may contain additional styles not specified in the provided code.
Inline CSS
Inline styles directly applied to individual h1 and h2 elements, setting color to red and font size to 20px.
Usage
Simply open the index.html file in a web browser to view the styled HTML document.

