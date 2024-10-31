<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Diwali Celebration</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #1e1e2f;
      color: #f4d03f;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    .container {
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }

    .heading {
      font-size: 3em;
      font-weight: bold;
      color: #f4d03f;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
      margin: 0;
    }

    .subheading {
      font-size: 1.5em;
      color: #ff8a65;
      margin: 0.5em 0 1.5em 0;
    }

    .fireworks {
      display: flex;
      justify-content: center;
      gap: 15px;
    }

    .firework {
      width: 10px;
      height: 10px;
      background-color: #ff8a65;
      border-radius: 50%;
      animation: explode 1s infinite ease-in-out;
    }

    .firework:nth-child(2) {
      background-color: #f4d03f;
      animation-delay: 0.5s;
    }

    .firework:nth-child(3) {
      background-color: #5DADE2;
      animation-delay: 1s;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes explode {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(2);
        opacity: 0.6;
      }
    }

    .footer {
      margin-top: 2em;
      font-size: 1em;
      color: #ffffff;
      opacity: 0.8;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="heading">Happy Diwali!</h1>
    <p class="subheading">Wishing you joy, prosperity, and light!</p>
    <div class="fireworks">
      <div class="firework"></div>
      <div class="firework"></div>
      <div class="firework"></div>
    </div>
    <p class="footer">May this Diwali bring joy and peace to you and your family.</p>BY Vikash singh
  </div>
</body>
</html>
