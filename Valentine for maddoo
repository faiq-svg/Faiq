<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Day, Maddoo! 💖</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Sacramento&display=swap');

        body {
            text-align: center;
            background: linear-gradient(to bottom, #ff9a9e, #fecfef);
            font-family: 'Sacramento', cursive;
            color: #fff;
            overflow: hidden;
        }
        h1 {
            font-size: 4rem;
            margin-top: 50px;
            text-shadow: 2px 2px 10px rgba(255, 255, 255, 0.8);
        }
        .heart {
            font-size: 60px;
            animation: heartbeat 1s infinite alternate;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            100% { transform: scale(1.3); }
        }
        .message {
            font-size: 2rem;
            margin-top: 20px;
            text-shadow: 2px 2px 8px rgba(255, 255, 255, 0.7);
        }
        button {
            background-color: #ff4d6d;
            color: white;
            border: none;
            padding: 12px 25px;
            font-size: 1.8rem;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 50px;
            font-family: 'Sacramento', cursive;
            transition: all 0.3s ease-in-out;
            box-shadow: 0 0 15px rgba(255, 77, 109, 0.8);
        }
        button:hover {
            background-color: #e63950;
            box-shadow: 0 0 20px rgba(255, 77, 109, 1);
            transform: scale(1.1);
        }
        .hidden {
            display: none;
            margin-top: 20px;
            font-size: 2.5rem;
            color: #fff;
            font-weight: bold;
            text-shadow: 2px 2px 10px rgba(255, 255, 255, 0.9);
        }

        /* Floating Hearts Animation */
        .hearts {
            position: absolute;
            width: 100%;
            height: 100%;
            overflow: hidden;
        }
        .hearts span {
            position: absolute;
            bottom: -10px;
            background-color: rgba(255, 77, 109, 0.8);
            width: 20px;
            height: 20px;
            border-radius: 50%;
            animation: floatUp 4s infinite linear;
        }
        @keyframes floatUp {
            0% { transform: translateY(0) scale(1); opacity: 1; }
            100% { transform: translateY(-100vh) scale(1.5); opacity: 0; }
        }
    </style>
</head>
<body>

    <h1>Happy Valentine's Day, Maddoo! 💕</h1>
    <div class="heart">💖</div>
    <p class="message">You make my world brighter and my heart happier! 😘</p>
    
    <button onclick="showMessage()">Click for a Surprise 💌</button>
    <p class="hidden" id="hiddenMessage">You are my everything, Maddoo! Forever and always! ❤️</p>

    <div class="hearts">
        <!-- Floating Hearts -->
        <script>
            function createHearts() {
                const hearts = document.querySelector('.hearts');
                for (let i = 0; i < 15; i++) {
                    let heart = document.createElement('span');
                    heart.style.left = Math.random() * 100 + "vw";
                    heart.style.animationDuration = Math.random() * 3 + 2 + "s";
                    hearts.appendChild(heart);
                }
            }
            createHearts();
        </script>
    </div>

    <script>
        function showMessage() {
            document.getElementById("hiddenMessage").style.display = "block";
        }
    </script>

</body>
</html>
