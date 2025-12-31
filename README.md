# my--project-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>For You 💖</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container" id="welcome">
    <h1>Welcome ✨</h1>
    <p>Please enter your first name</p>
    <input type="text" id="nameInput" placeholder="Your Name">
    <button onclick="enterSite()">Enter</button>
</div>

<div class="container hidden" id="card">
    <h2 id="dearText">Dear</h2>

    <img id="sunflowerImg"
         src="https://images.unsplash.com/photo-1508747703725-719777637510"
         alt="Sunflowers">

    <div class="buttons">
        <button onclick="toggleMode()">Change Mode</button>
        <button onclick="showMeaning()">Do you know why two sunflowers are used?</button>
    </div>

    <p id="meaning" class="hidden">
        When the sun is present, both sunflowers face the sun together.<br>
        When the sun is gone, they turn toward each other.<br><br>
        It means that even in the absence of light,
        they choose to support one another.
    </p>

    <p class="message">
        Thank you for coming into my life.<br><br>

        You are very important to me, so please stay with me in 2026 and beyond.<br><br>

        If I ever make any mistakes—whether knowingly or unknowingly—please forgive me.
        I know your heart is big, so give me a punishment if needed,
        or simply forgive me.<br><br>

        Thank you for making my life in 2025 so beautiful and meaningful.
    </p>

    <strong>Thank you, <span id="nameHere"></span> ❤️</strong>
</div>

<script src="script.js"></script>
</body>
</html>
