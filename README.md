Block Match Game

Play the Game(https://blockmatcher.vercel.app/)

The Block Match Game is a fun, interactive grid-based game where players drag and drop blocks to create matches of three identical images. Each successful match increases the score, and players aim to maximize their score before the timer runs out. This project uses HTML, CSS, and JavaScript for a seamless gaming experience on the web.

 How to Play
1. Objective: Match blocks of the same image by dragging and dropping them into place.
2. Scoring: Each match of three identical blocks will increase your score by 10 points.
3. Timer: The game lasts 60 seconds. Try to get the highest score possible before time runs out.
4. Restart: After the game ends, restart to try and beat your high score!

Features
- Drag-and-Drop: Drag and drop blocks to create matches within an 8x8 grid.
- Score and Timer Display: Track your score and remaining time as you play.
- Visual Feedback: Blocks animate briefly when matched to provide visual feedback.
- Responsive Design: Optimized for various screen sizes.

 Files
- `index.html`: HTML structure for the game layout.
- `style.css`: Styling for the game interface, scorecard, timer, and modal.
- `script.js`: JavaScript for grid creation, block swapping, match detection, and score updates.

 Technical Highlights
1. Dynamic Grid Creation: JavaScript creates an 8x8 grid where each block contains a random image.
2. Match Detection: Checks for rows and columns of three or more matching blocks.
3. Clear and Refill Blocks: Matched blocks are cleared and replaced with new images, maintaining an endless play cycle.
4. Timer and Score Updates: Regular updates to the score and timer encourage players to act fast and strategically.
5. Modal Popup: Displays the final score and a restart option when time is up.

## Game Mechanics
- Block Matching: Matches are detected by checking adjacent blocks horizontally and vertically.
- Score Increments: Each successful match increases the score by 10 points.
- Animated Matches: Matching blocks are highlighted with a "wiggle" animation before they are cleared.

## Future Enhancements
- High Score Tracking: Save the highest score to motivate players to improve.
- Levels: Add varying difficulty levels with unique challenges.

## Getting Started
1. Clone or download this repository.
2. Open `index.html` in a browser to play the game locally.
3. Or, play the live version at [https://blockmatcher.vercel.app/](https://blockmatcher.vercel.app/).

