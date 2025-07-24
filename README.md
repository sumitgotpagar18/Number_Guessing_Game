# Number_Guessing_Game

Number Guessing Game (Python)
A fun and interactive command-line Python game where the computer picks a random number within a specified range, and the player has a limited number of attempts to guess it correctly. After each guess, the program provides helpful feedback—indicating whether the player's guess is too high, too low, or correct—until they either succeed or run out of tries 

## Features

- Chooseable range (default: 1–100)

- Input validation ensures guesses are valid integers within bounds

- Friendly feedback (“Too high!”, “Too low!”)

- Limits the number of attempts (default: 10), with dynamic tracking of remaining tries

- Congratulatory message on win, or reveals the number if you lose

## How It Works

## Setup

- Use random.randint(lower, upper) to generate a secret number

- Initialize attempt counter (max_attempts = 10) 

## Guess Loop

- Prompt the player repeatedly for a guess in the defined range

- Validate input: ensure it's an integer within bounds

- Compare guess to the secret number:

- If lower → “Too low”

- If higher → “Too high”

- If correct → congratulate and exit

- Track attempts and inform the player of remaining chance

## Game End

- If guessed, show success with attempt count

- If not, reveal the secret number and end the game
