<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Encryption Project</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h2>Image Encryption & Decryption</h2>
        <input type="file" id="imageInput" accept="image/*">
        <br><br>
        <button onclick="encryptImage()">Encrypt Image</button>
        <button onclick="decryptImage()">Decrypt Image</button>
        <br><br>
        <canvas id="canvas"></canvas>
        <p id="output"></p>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.1.1/crypto-js.min.js"></script>
    <script src="script.js"></script>

</body>
</html>
