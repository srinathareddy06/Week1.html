<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basics of Web Development</title>
</head>

<style>
body {
    font-family: Arial, sans-serif;
    background-color: blue;
    margin: 0;
    padding: 0;
}

.container {
    width: 80%;
    margin: auto;
    padding: 20px;
    background: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

h1 {
    color: red;
}

h2 {
    color: lightpink;
}

.sample-img {
    width: 300px;
    margin: 10px 0;
}

button {
    padding: 10px 20px;
    background-color: #00796b;
    color: lightgreen;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: yellow;
}
</style>

<body>

  <div class="container">
        <h1>Basics of Web Development</h1>

  <h2>Create a Simple Webpage Using HTML</h2>
        <p>This is a simple webpage built using HTML. Below you can see headings, paragraphs, images, and a link.</p>

  <img src="C:\Users\Harinath Reddy\Desktop\sriclgid.jpg" alt="Sample Image" class="sample-img">

  <p>Click below to visit Google:</p>
        <a href="https://google.com" target="_blank">Go to Google</a>
    </div>

  <h2>Add Basic JavaScript for Interactivity</h2>
    <button onclick="showAlert()">Click Me</button>

  <script>
        function showAlert() {
            alert("Hello! This alert is triggered using JavaScript.");
        }
    </script>

</body>
</html>
