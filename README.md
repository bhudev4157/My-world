# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Special Message for You</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            background: linear-gradient(to bottom, #ffe6f2, #ffb3d9); /* Soft pink gradient background */
            color: #333;
        }
        h1 {
            color: #d63384;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .message {
            margin-top: 30px;
            font-size: 1.3em;
            font-style: italic;
            display: none; /* Hidden initially */
        }
        .stickers {
            margin-top: 20px;
            font-size: 2em;
        }
        button {
            background-color: #d63384;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 20px;
        }
        button:hover {
            background-color: #b02a6b;
        }
        audio {
            margin-top: 20px;
            width: 100%;
            max-width: 300px;
        }
    </style>
</head>
<body>
    <h1>Hey Pihuudaa, You're Not Alone</h1>
    <p>I know you've been feeling like you want to stay away from everyone, and that's okay. But I want you to know that I'm here for you, no matter what.</p>
    <button onclick="revealMessage()">Click to Open My Special Message</button>
    <div class="message" id="specialMessage">
        <p>You mean the world to me. Your smile lights up my day, and your friendship has been a constant source of joy in my life. Even if you're going through tough times, remember that you're loved and valued.</p>
        <p>I'm always just a message away. Let's talk whenever you're ready. You're not alone in this.</p>
    </div>
    <div class="stickers">
        🌟 💖 🌸 ✨ 😊 🌈
    </div>
    <p>With all my love, Bhudev</p>
    
    <!-- Background song: Hello Taqdeer (Violin) -->
    <audio controls autoplay loop>
        <source src="https://www.example.com/hello-taqdeer-violin.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <script>
        function revealMessage() {
            const message = document.getElementById('specialMessage');
            message.style.display = 'block';
        }
    </script>
</body>
</html>
