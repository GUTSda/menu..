<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>
  <style>
    body {
      background-color: aquamarine; /* Aquamarine background for the menu */
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    .menu {
      padding: 20px;
      text-align: center;
    }
    .button {
      background-color: #4CAF50;
      color: #fff;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .button:hover {
      background-color: #3e8e41;
    }
    ul {
      list-style-type: none; /* Remove bullet points */
      padding: 0; /* Remove padding */
    }
    li {
      display: inline; /* Display list items inline */
      margin: 0 15px; /* Add margin between items */
    }
  </style>
</head>
<body>
  <div class="menu">
    <h1>My Website</h1>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <button class="button" onclick="location.href='synopsis.html'">Synopsis</button>
  </div>
</body>
</html>
