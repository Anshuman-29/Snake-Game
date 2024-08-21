## Nokia Snake Game Web Application

This project is a web-based implementation of the classic Nokia Snake game, built using HTML, CSS, and JavaScript. The game is a nostalgic recreation that allows users to control a snake, collect food, and grow in length while avoiding collisions with the walls or the snake's own body. The game also includes features like a "Start" button, score tracking, and persistent high scores.

### Features

- **Responsive Snake Controls**: Use the arrow keys (UP, DOWN, LEFT, RIGHT) to control the snake's movement.
- **Food Generation**: The game generates food at random positions on the grid. Every time the snake eats the food, it grows by one unit.
- **Start Button**: The game only begins when the "START" button is clicked, allowing the player to prepare before gameplay starts.
- **Score Tracking**: The game tracks the current score, the number of games played, and the highest score achieved.
- **Persistent High Score**: The high score is stored in the browser's local storage, ensuring it is preserved across sessions.
- **Textured Snake**: The snake is visually enhanced with an alternating light and dark green texture to add depth to the game.
- **Game Over Alerts**: If the snake collides with the walls or itself, the game ends with an alert, and the score is updated.

### How to Play

1. Open the game in your browser.
2. Click the "START" button to begin the game.
3. Use the arrow keys to control the snake's movement.
4. Eat the red food squares to grow the snake and increase your score.
5. Avoid collisions with the walls or the snake's own body to prevent a game over.
6. The high score is saved and displayed each time you play the game.

### Technology Stack

- **HTML**: Structure of the web page.
- **CSS**: Styling for the game interface and snake texture.
- **JavaScript**: Game logic, score tracking, and key event handling.

### Installation

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/nokia-snake-game.git
   ```
2. Open the `index.html` file in your preferred web browser.

### Future Enhancements

- Add sound effects for game events like eating food or game over.
- Implement different levels or difficulty settings.
- Create a mobile-friendly version with touch controls.

---
