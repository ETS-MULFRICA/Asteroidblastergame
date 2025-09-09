CHELSEA BISALLA
Task: A LIVE GAME
The Asteroid Blaster Game is a browser-based arcade-style shooting game inspired by the classic Asteroids. It was developed using HTML, CSS, and JavaScript and is playable directly in a web browser without requiring any additional software installations. The game demonstrates the use of front-end web technologies, basic game physics, collision detection, and interactive controls.
Objective of the Game
The player controls the spaceship with the goal of:
-Navigating through space,
-Avoiding collisions with asteroids, and
-Shooting bullets to destroy asteroids for points.
The game ends when the player loses all available lives.
TECHNOLOGIES USED
HTML: Provides the structure and the <canvas> element where the game is rendered.
CSS: Used for styling the interface elements such as the score display, buttons, and background.
JavaScript: Implements the game logic, including movement, shooting, asteroid spawning, collision detection, scoring system, and rendering updates.
Game Features
Spaceship Controls:
-Rotate left/right with the arrow keys.
-Apply thrust with the up arrow key.
-Shoot bullets with the spacebar.
Asteroids:
-Appear randomly and drift across the screen.
-Larger asteroids split into smaller ones when destroyed.
Collisions: If the ship collides with an asteroid, the player loses a life.
Scoring System:
-Points are awarded when asteroids are destroyed.
User Interface:
-Start button, Pause/Resume, Mute, and on-screen score/lives tracker.
Game Loop:
-Runs at ~60 frames per second to ensure smooth gameplay.
HOW THE GAME WORKS.
The game initializes by creating the spaceship object at the center of the canvas.
Asteroids are randomly generated and move with independent velocities.
User input (keyboard events) controls the spaceship’s angle, thrust, and bullets.
A game loop continuously updates positions of all objects, checks for collisions, and redraws the canvas.
Collision detection is radius-based: if the distance between two objects (ship/asteroid or bullet/asteroid) is less than the sum of their radii, a collision occurs.
On collision:
-Bullets destroy asteroids, splitting them.
-The ship colliding with an asteroid results in losing a life.
The current version implements the core gameplay successfully. Additional features such as sound effects, multiple levels, and mobile touch controls could be considered for future versions if the game is expanded further.
Challenges faced:
-A challenge I faced was understanding how to apply basic physics concepts (movement, thrust, velocity, and collisions) using JavaScript. Translating these concepts into working code required extra research and practice, making sure the game would be as interactive as it could get.
-As I am still growing my knowledge in HTML, CSS, and JavaScript, I had to spend extra effort learning the syntax and logic while implementing the game.

