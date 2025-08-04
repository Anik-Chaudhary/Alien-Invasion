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

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/37935d96-88af-41a1-a7de-9bd74d0b6f21/tempCodeRunnerFile.py
[2] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/eb670a8f-5b85-4ebb-8bd1-4f39e42c45de/alien_invasion.py
[3] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/a4af18b0-2feb-46c4-a717-e650548cce9f/scoreboard.py
[4] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/b143247f-ff49-4e29-8950-4998f616176d/ship.py
[5] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/7411dd11-0aaf-4c11-9313-64274b1e2abf/settings.py
[6] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/9517cebb-0804-44d1-9774-a98db1c85f66/game_stats.py
[7] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/795f317e-960e-4917-b668-7bc106f7bd62/button.py
[8] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/e80fbf38-8854-42c0-bafe-2fb5a99443aa/alien.py
[9] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83675536/3734e4ca-878f-457a-81e5-333278c0d278/bullet.py
[10] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/83675536/d311d7b7-2057-48ec-b7b6-379d98762dd4/alien.jpg?AWSAccessKeyId=ASIA2F3EMEYESS3XM634&Signature=JoR9OYtTMpMrDJCFRsRfVl%2FfUyY%3D&x-amz-security-token=IQoJb3JpZ2luX2VjEA4aCXVzLWVhc3QtMSJIMEYCIQCTQEbFF%2BChlqjjsf34dS5RM7q6mfZSHUS2GgO2b%2BdEygIhAIzljfyifDoT2sMjGLGjj4lDYrsLjYeh70mXf%2FHvBw5JKvEECEYQARoMNjk5NzUzMzA5NzA1IgzMAhpHOKhb7CAC0HMqzgRIom80Ku48tEhO0hp3bTJJgQpozB2N2K8ckGJIfVURMTZFbe6kT4AO4Jv%2FjvyxWXguKqhNHMmd7PLS8B3G4Z314dSH5y9lkGQKozkN5AvIqgo%2FXC9ISLOUmi4uve%2BjBeKMV%2FV7yRNIwQOEWWIlZhLxtRV7sD5cES%2BVNYJ3vg0SrNnw4S3zBcv7%2FMviIc5stco911xNNtb3rypeDyrYgAsWtsOP%2FWGTZYsTHbJrk0Ck4RRx5rv1kzmU82gUvNukvA46VI5JzvJQO0fHcM47AgKl4Rmo23jIN8lO68pr6OpnF%2FeWMy%2FiuMfnfx3Zbr%2BQGeuAyg%2F2Bydce54t19u7VcdjiGeQGTvYC7kjP3s1nQBF3GZSp1PDn5kkB0ZN3RcqTFNigQDvtY2AukgAxz7VT%2Fu962ZuO3qJa%2BOPJZ83DBq7Qq6%2B1ffjmW%2FzouKLdfxgE2OfU68%2BQBN26mzgsGGAE6fx46SWkUXLmwATmzr%2FeBpcCbMLV2cR6leMlIX%2FQy33P8IZaYzjvBklB7yF6DLLfN0Tu%2FFJnMMr0VINamj%2FtPUj%2FmIcc12GywCH%2BJZSdJoIGkPkrf6IOqAZjejXYxeyHkrj8o5rYbbH7N72sS83IAJzVtziUaSJUkVg5dKvzBouQec4fPL4V3j5ejxF54QhAwM4DYaBxoTXndCYPjwnJSSEJob%2BtVyx0kVme5hNl7E0btnwAv0EwmiTG9cC5IwI5%2Fixwf7IDgJwSlzXaGDaYSL%2FdCrCkxW2cFUxQ1RB9ROSdtXbJmmL5YBBsxdPSRkptTC45MLEBjqZAe8az98yrTe%2F5re5rXZSiPG4QcWFAVygrEcln2R2lcJTkdCYWnKJP4z9fc9KbroSgefdyYiQA4sRJix9nmkoQcCqMlFTiEjb2FTdZlAClAteNYLs9opzqxklOJmgSdJDEogjbFwPra2KE1L11F%2Fa2Yr5wddRxGnQfCqetX%2B%2F1hRpyVQo3Y%2BRU5DY4IQqnI9ona4YuZbri%2FiTzA%3D%3D&Expires=1754314182
[11] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/images/83675536/6f8b9a1c-f3a6-4531-a2a3-bc4444927724/ship.jpg?AWSAccessKeyId=ASIA2F3EMEYESS3XM634&Signature=hIMTgrSQ3%2F5dVwwuwyckoYeeisE%3D&x-amz-security-token=IQoJb3JpZ2luX2VjEA4aCXVzLWVhc3QtMSJIMEYCIQCTQEbFF%2BChlqjjsf34dS5RM7q6mfZSHUS2GgO2b%2BdEygIhAIzljfyifDoT2sMjGLGjj4lDYrsLjYeh70mXf%2FHvBw5JKvEECEYQARoMNjk5NzUzMzA5NzA1IgzMAhpHOKhb7CAC0HMqzgRIom80Ku48tEhO0hp3bTJJgQpozB2N2K8ckGJIfVURMTZFbe6kT4AO4Jv%2FjvyxWXguKqhNHMmd7PLS8B3G4Z314dSH5y9lkGQKozkN5AvIqgo%2FXC9ISLOUmi4uve%2BjBeKMV%2FV7yRNIwQOEWWIlZhLxtRV7sD5cES%2BVNYJ3vg0SrNnw4S3zBcv7%2FMviIc5stco911xNNtb3rypeDyrYgAsWtsOP%2FWGTZYsTHbJrk0Ck4RRx5rv1kzmU82gUvNukvA46VI5JzvJQO0fHcM47AgKl4Rmo23jIN8lO68pr6OpnF%2FeWMy%2FiuMfnfx3Zbr%2BQGeuAyg%2F2Bydce54t19u7VcdjiGeQGTvYC7kjP3s1nQBF3GZSp1PDn5kkB0ZN3RcqTFNigQDvtY2AukgAxz7VT%2Fu962ZuO3qJa%2BOPJZ83DBq7Qq6%2B1ffjmW%2FzouKLdfxgE2OfU68%2BQBN26mzgsGGAE6fx46SWkUXLmwATmzr%2FeBpcCbMLV2cR6leMlIX%2FQy33P8IZaYzjvBklB7yF6DLLfN0Tu%2FFJnMMr0VINamj%2FtPUj%2FmIcc12GywCH%2BJZSdJoIGkPkrf6IOqAZjejXYxeyHkrj8o5rYbbH7N72sS83IAJzVtziUaSJUkVg5dKvzBouQec4fPL4V3j5ejxF54QhAwM4DYaBxoTXndCYPjwnJSSEJob%2BtVyx0kVme5hNl7E0btnwAv0EwmiTG9cC5IwI5%2Fixwf7IDgJwSlzXaGDaYSL%2FdCrCkxW2cFUxQ1RB9ROSdtXbJmmL5YBBsxdPSRkptTC45MLEBjqZAe8az98yrTe%2F5re5rXZSiPG4QcWFAVygrEcln2R2lcJTkdCYWnKJP4z9fc9KbroSgefdyYiQA4sRJix9nmkoQcCqMlFTiEjb2FTdZlAClAteNYLs9opzqxklOJmgSdJDEogjbFwPra2KE1L11F%2Fa2Yr5wddRxGnQfCqetX%2B%2F1hRpyVQo3Y%2BRU5DY4IQqnI9ona4YuZbri%2FiTzA%3D%3D&Expires=1754314182
