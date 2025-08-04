# Alien Invasion

Alien Invasion is a classic arcade-style game developed with Python and Pygame, inspired by the vintage Space Invaders gameplay. Control your spaceship, dodge and shoot waves of incoming aliens, and aim for the highest score!

## Game Features

- **Smooth Controls:** Move your ship left or right and fire bullets to destroy alien fleets.
- **Dynamic Levels:** The game speeds up and aliens become more valuable as you progress through levels.
- **Scorekeeping:** Earn points for each alien destroyed. Track your current and highest scores.
- **Life System:** Lose a ship if an alien hits you or reaches the bottom. The game ends when you run out of ships.
- **Fullscreen Experience:** The game automatically adjusts to your screen size.
- **User Interface:** A Play button lets you start or restart the action.

## Screenshots

### Alien Sprite
![Green alien Ship Sprite
![Ship sprite Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/alien-invasion.git
   cd alien-invasion
   ```

2. **Install dependencies:**
   - Make sure you have [Python 3.x](https://www.python.org/downloads/) installed.
   - Install [Pygame](https://www.pygame.org/wiki/GettingStarted):
     ```bash
     pip install pygame
     ```

3. **Add game images:**
   - Place your `alien.bmp` and `ship.bmp` images in a folder named `images` inside the repository.
   - Example provided images:
     - ![Alien](attached 
     - ![Ship](attached_image to Play

- **Move left or right:** Press the arrow keys (`←`/`→`).
- **Fire bullets:** Press the spacebar.
- **Quit game:** Press `Q` or use the window's close button.
- **Start New Game:** Click the "Play" button when the game is inactive.

## Code Structure

- `alien_invasion.py`: Main game logic and event loop.
- `settings.py`: All configuration for gameplay (speed, colors, etc).
- `game_stats.py`: Tracks score, lives, and levels.
- `scoreboard.py`: Renders score and level to the screen.
- `button.py`: The Play button.
- `ship.py`: Ship sprite and movement logic.
- `alien.py`: Alien sprite and movement logic.
- `bullet.py`: Bullet behavior and rendering.

## Credits

- Sprites: Custom or public domain, can be swapped out in the `images` folder.
- Inspired by "Python Crash Course" by Eric Matthes.

## License

[MIT License](LICENSE)

Enjoy defending the Earth in Alien Invasion! 🚀👾
