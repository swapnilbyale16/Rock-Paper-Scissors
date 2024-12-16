# Rock Paper Scissors Game

## Overview
This is a classic Rock Paper Scissors game implemented using HTML, CSS, and JavaScript. Players can compete against the computer, and the game dynamically calculates and displays the results of each round.

---

## Features
- **User Choices:** Players can choose Rock, Paper, or Scissors by clicking on the corresponding option.
- **Computer Choice:** The computer randomly selects its move.
- **Game Outcome:** The game announces whether the player won, lost, or tied the round.
- **Scoreboard:** Tracks the player's and computer's scores dynamically.
- **Responsive Design:** Adaptable to different screen sizes.

---

## File Structure
### `index.html`
The main HTML file contains:
- A header with the game title.
- Choice buttons for Rock, Paper, and Scissors, each represented by an image.
- A scoreboard displaying the user’s and computer’s scores.
- A message container to announce the results of each round.

### `style.css`
Provides styling for:
- The layout of the game and scoreboard.
- The choice buttons and images.
- The result message container, including color changes based on the game outcome.

### `app.js`
Handles the game logic and interactivity:
- Listens for user input (button clicks).
- Generates a random choice for the computer.
- Determines the winner based on game rules.
- Updates the scoreboard and displays messages dynamically.

---

## How to Play
1. Open `index.html` in a web browser.
2. Click on one of the options: Rock, Paper, or Scissors.
3. The computer will randomly choose its move.
4. The result of the round (win, loss, or draw) will be displayed, and the scores will be updated.

---

## Game Rules
- **Rock beats Scissors**
- **Paper beats Rock**
- **Scissors beats Paper**
- If both the player and computer choose the same option, the round is a draw.

---

## Dependencies
No external libraries or frameworks are required. The game uses:
- JavaScript for logic.
- HTML and CSS for structure and styling.

---

## Future Improvements
- Add a "Best of N" mode to determine the overall winner after several rounds.
- Enhance UI with animations and sound effects.
- Implement difficulty levels for the computer's choices.
- Make the game mobile-friendly with touch interactions.

---

## Author
This Rock Paper Scissors game is developed as a fun project to practice JavaScript and web development skills.

