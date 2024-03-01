<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Guessing Game</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Guess the Number!</h1>
        <p id="message">Guess a number between 1 and 10</p>
        <input type="number" id="guessInput" placeholder="Enter your guess">
        <button onclick="checkGuess()">Submit Guess</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
