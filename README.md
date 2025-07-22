Streemo.html  File

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Welcome to My Webpage</h1>
        <p>This is a simple HTML, CSS, and JavaScript example.</p>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>I am learning how to build websites using HTML, CSS, and JavaScript.</p>
            <img src="C:\Users\tetal\OneDrive\Desktop\IMAGES\th.jpeg" alt="th">
        </section>

        <section>
            <h2>My Favorite Site</h2>
            <p>Visit <a href= "https://aknu.edu.in/Exams/results.php">Aknu site</a> to see the results.</p>
        </section>

        <section>
            <h2>Click the Button</h2>
            <button onclick="showMessage()">Click Me!</button>
        </section>
    </main>

    <footer>
        <p>© 2025 My First Website</p>
    </footer>

    <script src="javascript.js"></script>
</body>
</html>


styles.css  file

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f0f4f8;
    color: #333;
}

header {
    background-color: #0077cc;
    color: white;
    padding: 20px;
    text-align: center;
}

main {
    padding: 20px;
}

h2 {
    color: #0077cc;
}

img {
    max-width: 100%;
    height: auto;
    display: block;
    margin-top: 10px;
}

button {
    background-color: #28a745;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 16px;
    margin-top: 10px;
}

button:hover {
    background-color: #218838;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}


javascript.js  file


function showMessage() {
    alert("Hello! You clicked the button.");
}



output:
Welcome to My Webpage
This is a simple HTML, CSS, and JavaScript example.

About Me
I am learning how to build websites using HTML, CSS, and JavaScript.

th
My Favorite Site
Visit Aknu site to see the results.

Click the Button
Click Me!
© 2025 My First Website


