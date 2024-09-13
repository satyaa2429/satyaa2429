<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Assignment 2</title>
    <style>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
    color: #333;
}
header {
    text-align: center;
    padding: 20px;
    background-color: #4CAF50;
    color: white;
}
h1 {
    margin: 0;
}
h2 {
    color: #4CAF50;
}
.color-demo, .background-demo, .gradient-demo, .image-demo {
    margin: 20px;
    padding: 20px;
    border-radius: 8px;
}
.text-color {
     background: linear-gradient(to right, #FF5733, #FFC300); /* Gradient background */
    padding: 20px;
    border-radius: 8px;
    color: white;
}
.background-color {
    background-color: #FFD700; /* Solid background color */
    padding: 20px;
    border-radius: 8px;
}
.gradient-background {
    background: linear-gradient(to right, #FF5733, #FFC300); /* Gradient background */
    padding: 20px;
    border-radius: 8px;
    color: white;
}
.background-image {
    background-color: #FFD700;
    background-image: url('https://via.placeholder.com/300'); /* Background image */
    background-repeat: no-repeat; /* No repeat */
    background-position: center; /* Center the image */
    background-size: cover; /* Cover the entire div */
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    border-radius: 8px;
}
    </style>
</head>
<body>
    <header>
        <h1>CSS Assignent 2</h1>
    </header>
    <section class="color-demo">
        <h2>Text Color</h2>
        <p class="text-color">This text is styled with a specific color.</p>
    </section>
    <section class="background-demo">
        <h2 >Background Color</h2>
        <div class="background-color">This div has a solid background color.</div>
    </section>
    <section class="gradient-demo">
        <h2>Gradient Background</h2>
        <div class="gradient-background">This div has a gradient background.</div>
    </section>
    <section class="image-demo">
        <h2>Background Image</h2>
        <div class="background-image">This div has a background image.</div>
    </section>
    <footer>
        <p>Experimenting with CSS color properties!</p>
    </footer>
</body>
</html>

