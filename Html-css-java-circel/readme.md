<!-- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML, CSS, JS Venn Diagram</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="circle html">
            <img class="html-logo" src="./assest/html.png" alt="HTMLLogo">
            <span class="html-label">HTML</span>
        </div>
        <div class="circle css">
            <span class="css-label">CSS</span>
            <img class="css-logo" src="./assest/css.png" alt="CSS Logo">
        </div>
        <div class="circle js">
            <img class="java" src="./assest/javascript.png" alt="JavaScript Logo">
        </div>
    </div>
</body>
</html> -->



/* Body Styling */
body {
    background: linear-gradient(to bottom, #1a237e, #283593);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

/* Container */
.container {
    position: relative;
    width: 500px;
    height: 500px;
}

/* Circle Common Styling */
.circle {
    width: 250px;  /* Increased size */
    height: 250px; /* Increased size */
    border-radius: 50%;
    position: absolute;
    display: flex;
    justify-content: center;
    align-items: center;
    background: transparent;
    opacity: 0.9; /* Slight transparency for overlap effect */
}

/* Individual Circle Colors and Positioning */
.html {
    border: 8px solid #ff5722; /* HTML Orange */
    top: 50px;
    left: 125px;
}
.css {
    border: 8px solid #2196f3; /* CSS Blue */
    top: 180px;
    left: 20px;
}

.js {
    border: 8px solid #ffeb3b; /* JS Yellow */
    top: 180px;
    right: 20px;
}

/* Logo Styling */
img {
    width: 75px;  /* Increased size */
    height: auto;
}

/* Labels */
.html-label {
    position: absolute;
    top: -30px;
    font-size: 22px;
    font-weight: bold;
    color: white;
    text-transform: uppercase;
}

.css-label {
    position: absolute;
    top: -30px;
    font-size: 22px;
    font-weight: bold;
    color: white;
    text-transform: uppercase;
}