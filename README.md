<!DOCTYPE html>
<html>
<head>
  <title>HTML Elements and CSS Selectors</title>
  <link rel="stylesheet" href="Css Assignment.css">
</head>
  <style>
   *{
    padding: 0;
    margin:0;
    box-sizing: border-box;}

body{
    font-family: Arial, Helvetica, sans-serif;
    padding: 0;
}
    /* Element selector */
    h1 {
      font-family: Arial, sans-serif;
      line-height: 1.5;
      color: brown;
      background-color: burlywood;
      text-align: center;
    }

    h2{font-family: Arial, sans-serif;
        line-height: 1.5;
        color: black;
        background-color: burlywood;
        text-align: center;

    }
    /* Class selector */
    .satya {
      background-color:beige;
      font-weight: bold;
      color: blue;
      text-align: center;
    }

    /* ID selector */
    #mine {
      color: blue;
      font-size: 20px;
      background-color: aqua;
      text-align: center;
    }
 

    /* Pseudo-class selector */
    a:hover {
      color: red;
    }

    /* Pseudo-element selector */
    p::first-line {
      font-weight: bold;
    }
   
  </style>
<body>
  <h1>main heading</h1>

  <h2>sub heading</h2>
  <p class="satya">The HTML element represents a paragraph. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank lines and/or first-line indentation,
     but HTML paragraphs can be any structural grouping of related content, such as images or form fields.</p>
  
  <p class="satya">Color of text for hyperlinks when selected.
     Do not use this attribute! Use the CSS color property in conjunction with the :active pseudo-class instead.</p>
  <ul>
    <li><a href="https://www.example.com" >Website</a></li>
    <li><a href="https://www.google.com" >Google</a></li>
  </ul>

  <p id="mine">This is a unique paragraph element.</p>
</body>
</html>
