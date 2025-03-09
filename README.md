# FoodInsta---Full-Stack-Food-Delivery-Application

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FoodInsta - Online Food Order & Delivery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(120deg, #fdfbfb, #ebedee);
            text-align: center;
            color: #333;
            overflow-x: hidden;
        }
        h1 {
            font-size: 2.5em;
            margin-top: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }
        .snapshots {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
        }
        .snapshots img {
            width: 200px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }
        .snapshots img:hover {
            transform: scale(1.1);
        }
        .animated-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://source.unsplash.com/1600x900/?food') no-repeat center center/cover;
            opacity: 0.1;
            z-index: -1;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .fade-in {
            animation: fadeIn 1.5s ease-in-out;
        }
    </style>
</head>
<body>
    <div class="animated-bg"></div>
    <div class="container">
        <h1 class="fade-in">FoodInsta 🍔</h1>
        <p class="fade-in">A sleek and intuitive online food ordering and delivery application.</p>
        <h2 class="fade-in">🚀 Features</h2>
        <ul class="fade-in" style="list-style-type:none; padding: 0;">
            <li>🍕 Browse and order from a variety of restaurants</li>
            <li>🛵 Real-time order tracking</li>
            <li>💳 Secure online payments</li>
            <li>🌎 Location-based restaurant recommendations</li>
        </ul>
        <h2 class="fade-in">📸 Snapshots</h2>
        <div class="snapshots fade-in">
            <img src="snapshot1.jpg" alt="Snapshot 1">
            <img src="snapshot2.jpg" alt="Snapshot 2">
            <img src="snapshot3.jpg" alt="Snapshot 3">
        </div>
        <h2 class="fade-in">💻 Tech Stack</h2>
        <p class="fade-in">MERN Stack (MongoDB, Express.js, React.js, Node.js)</p>
    </div>
</body>
</html>
