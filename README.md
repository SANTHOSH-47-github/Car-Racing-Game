# Car Racing Game

A fun and interactive **2D car racing game** built using **HTML, CSS,
and JavaScript**.\
The player controls a car, avoids enemy vehicles, and scores points as
long as they survive. The game features **increasing difficulty,
pause/resume support, and high-score tracking**.

------------------------------------------------------------------------

## Features

-   **Start / Restart Game** with one click\
-   **Arrow key controls** for smooth car movement\
-   **Pause/Resume** with the spacebar\
-   **Enemy cars** with random colors and positions\
-   **Scrolling road effect** using moving divider lines\
-   **Increasing difficulty** -- speed rises as the score increases\
-   **High Score tracking** using `localStorage`\
-   **Responsive design** -- works on desktop and mobile screens

------------------------------------------------------------------------

## Gameplay Preview

-   Player car starts in the center of the road\
-   Enemy cars spawn randomly and move downward\
-   Colliding with an enemy ends the game\
-   The longer you play, the higher your score -- but the game gets
    faster!

------------------------------------------------------------------------

## How It Works

1.  **HTML (`index.html`)** -- Game structure (game area, score display,
    start button, pause screen).\
2.  **CSS (`styles.css`)** -- Styling for the game area, car, enemies,
    animations, and responsiveness.\
3.  **JavaScript (`script.js`)** -- Core logic:
    -   Handles keyboard input\
    -   Moves the car, enemies, and road lines\
    -   Checks collisions\
    -   Updates score and speed\
    -   Manages game start, pause, and end states

------------------------------------------------------------------------

## Controls

-   **Arrow Up** → Move car up\
-   **Arrow Down** → Move car down\
-   **Arrow Left** → Move car left\
-   **Arrow Right** → Move car right\
-   **Spacebar** → Pause / Resume the game

------------------------------------------------------------------------

## How to Run

1.  Clone the repo or download the files.\
2.  Open `index.html` in your browser.\
3.  Click **Start** to begin playing.

------------------------------------------------------------------------

## Future Improvements (Ideas)

-   Add different car models or themes\
-   Power-ups (speed boost, shield, etc.)\
-   Sound effects and background music\
-   Multiple levels with changing backgrounds\
-   Leaderboard system
