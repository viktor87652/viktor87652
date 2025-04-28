<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ANI MONKEY</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Roboto', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-image: url('https://images.unsplash.com/photo-1606112219348-204d7d8b94ee');
            background-size: cover;
            background-position: center;
            color: #fff;
            text-align: center;
            transition: background-image 0.5s ease-in-out;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 20px;
            background: rgba(0, 0, 0, 0.6);
            padding: 10px 20px;
            border-radius: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
            animation: fadeIn 1s ease-out;
        }
        .choices {
            display: flex;
            flex-direction: column;
            justify-content: center;
            margin-top: 30px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
            font-size: 1.5em;
            cursor: pointer;
            transition: transform 0.3s ease, background-color 0.3s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        button:hover {
            transform: scale(1.1);
            background-color: #45a049;
        }
        button:active {
            transform: scale(1.05);
            background-color: #388e3c;
        }
        #result {
            margin-top: 30px;
            font-size: 1.5em;
            font-weight: bold;
            background: rgba(0, 0, 0, 0.6);
            padding: 10px;
            border-radius: 10px;
            opacity: 0;
            animation: fadeIn 1s forwards;
        }
        #scoreboard {
            margin-bottom: 20px;
            font-size: 1.2em;
            font-weight: bold;
            background: rgba(0, 0, 0, 0.6);
            padding: 10px;
            border-radius: 10px;
        }
        #numberGuessGame {
            margin-top: 50px;
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
        }
        .input-field {
            margin: 10px 0;
            padding: 10px;
            font-size: 1.2em;
            width: 80%;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>

<h1>ANI MONKEY</h1>

<!-- Scoreboard for Rock Paper Scissors -->
<div id="scoreboard">
    <p>Player Score: <span id="scorePlayer">0</span></p>
    <p>Computer Score: <span id="scoreComputer">0</span></p>
</div>

<!-- Rock Paper Scissors Game -->
<div class="choices">
    <button onclick="play('rock')">Rock 🪨</button>
    <button onclick="play('paper')">Paper 📄</button>
    <button onclick="play('scissors')">Scissors ✂️</button>
</div>

<!-- Result for Rock Paper Scissors -->
<div id="result"></div>

<!-- Number Guessing Game -->
<div id="numberGuessGame">
    <h2>Number Guessing Game</h2>
    <p>Guess a number between 1 and 100!</p>
    <input type="number" id="guessInput" class="input-field" placeholder="Enter your guess" />
    <button onclick="guessNumber()">Guess</button>
    <div id="numberResult"></div>
</div>

<!-- Sound Effects -->
<audio id="fartSound" src="fart-sound.mp3"></audio>

<script>
// Rock Paper Scissors Game Variables
let playerScore = 0;
let computerScore = 0;

// Rock Paper Scissors Function
function play(playerChoice) {
    const choices = ['rock', 'paper', 'scissors'];
    const computerChoice = choices[Math.floor(Math.random() * 3)];

    let result = '';
    if (playerChoice === computerChoice) {
        result = 'It\'s a tie!';
    } else if (
        (playerChoice === 'rock' && computerChoice === 'scissors') ||
        (playerChoice === 'paper' && computerChoice === 'rock') ||
        (playerChoice === 'scissors' && computerChoice === 'paper')
    ) {
        result = 'You win!';
        playerScore++;
        document.getElementById('scorePlayer').textContent = playerScore;
    } else {
        result = 'You lose!';
        computerScore++;
        document.getElementById('scoreComputer').textContent = computerScore;
    }

    // Play sound effect
    const fartSound = document.getElementById('fartSound');
    fartSound.play();

    const resultDiv = document.getElementById('result');
    resultDiv.innerHTML = `You: ${playerChoice} | Computer: ${computerChoice} <br><strong>${result}</strong>`;

    resultDiv.style.animation = 'none';
    resultDiv.offsetHeight; // trigger reflow
    resultDiv.style.animation = 'fadeIn 1s forwards';
}

// Number Guessing Game Variables
let randomNumber = Math.floor(Math.random() * 100) + 1;
let attempts = 0;

// Number Guessing Function
function guessNumber() {
    const guess = document.getElementById('guessInput').value;
    const resultDiv = document.getElementById('numberResult');

    if (guess < randomNumber) {
        resultDiv.innerHTML = 'Too low! Try again.';
    } else if (guess > randomNumber) {
        resultDiv.innerHTML = 'Too high! Try again.';
    } else {
        resultDiv.innerHTML = `Congratulations! You guessed the number in ${attempts + 1} attempts!`;
        randomNumber = Math.floor(Math.random() * 100) + 1;  // Generate new random number
        attempts = 0; // Reset attempts
    }

    attempts++;
}
</script>

</body>
</html>
