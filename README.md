<!DOCTYPE html>
<html>
<head>
    <title>Zewdu's First Project</title>
    <style>
        body {
            background: linear-gradient(135deg, #FF4500, #FF8C00);
            font-family: 'Segoe UI', Arial, sans-serif;
            text-align: center;
            padding: 100px;
            color: white;
            min-height: 100vh;
            margin: 0;
        }
        .container {
            background: rgba(0,0,0,0.7);
            padding: 50px;
            border-radius: 30px;
            display: inline-block;
            animation: fadeIn 1.5s;
        }
        h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        .highlight {
            color: #FFD700;
            font-size: 24px;
        }
        button {
            background: #00BFFF;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            margin-top: 20px;
            transition: 0.3s;
        }
        button:hover {
            background: #FFD700;
            color: black;
            transform: scale(1.1);
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-50px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🔥 Zewdu Zemedu 🔥</h1>
        <p class="highlight">Computer Science Student at DBU</p>
        <p>🇪🇹 Debre Berhan University, Ethiopia 🇪🇹</p>
        <p>Welcome to my first GitHub project!</p>
        <p>I love coding, solving problems, and building amazing things.</p>
        <button onclick="alert('Thank you for visiting my project! - Zewdu')">Click Me!</button>
    </div>
</body>
</html>
