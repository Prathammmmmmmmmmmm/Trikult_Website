# Trikult_Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TRIKULT</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #111;
            color: white;
            font-family: Arial, sans-serif;
        }
        .logo-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 200px;
        }
        .logo {
            width: 150px;
            opacity: 0;
            transform: scale(0.5);
            animation: scaleUp 1s ease-out forwards;
        }
        @keyframes scaleUp {
            0% {
                opacity: 0;
                transform: scale(0.5);
            }
            100% {
                opacity: 1;
                transform: scale(1);
            }
        }
    </style>
</head>
<body>
    <div class="logo-container">
        <img src="logo.png" alt="TRIKULT Logo" class="logo">
    </div>
    <h1>Welcome to TRIKULT</h1>
</body>
</html>
