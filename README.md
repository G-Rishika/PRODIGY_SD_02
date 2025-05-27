Number Guessing Game

This is a simple web-based application where the user tries to guess a randomly generated number between 1 and 100. The game provides real-time feedback and tracks the user's best score across sessions using browser storage.

Features

  Generates a random number between 1 and 100.
  Provides feedback on each guess: too high, too low, or correct.
  Tracks the number of attempts per round.
  Stores and displays the best score (fewest attempts).
  Reset button allows the user to start a new game without reloading the page.

Technologies Used

  HTML5 – For page structure.
  CSS3 – For styling and layout.
  JavaScript (ES6) – For game logic and interactivity.
  Web Storage API – To persist the best score in localStorage.

How to Play

  Enter a number between 1 and 100 in the input field.
  Click Submit Guess.
  Read the feedback and continue guessing until you get it right.
  After a correct guess, the game checks if it's your best score.
  Use Reset Game to start a new round.
