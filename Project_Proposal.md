## Name of the game
Asteroid Battle (subject to change because I suck at naming things)
## Short description of gameplay
* Two-player competitive game based on the classic Asteroids.  However, a player's gun has no effect on the other player and does not destroy asteroids; instead it changes a shot asteroid to the player's color.  When players collide with an asteroid of their own color, it splits.  Colliding with an asteroid of the neutral or other player's color destroys the player.  Colliding with the other player bounces both players.
* (Possible addition)  Limited ammo for the guns.
## Win condition
The other player is destroyed.
## Lose condition
You are destroyed.
## How the player interacts with the game
* Player Blue controls his ship via W (forward thrust), A (rotate left), D (rotate right), and LeftControl/Space (shoot).
* Player Red uses Numpad-8, Numpad-4, Numpad-6, and Numpad-0/Numpad-Enter, respectively, for the same controls.
## List of game features (similar to the feature list we drafted for our platformer game)
* MenuState - Just waiting to start the game
* PlayState - game field containing the players, asteroids, bullets, etc
* Players - handles the player sprites, input, movement, etc
* Asteroids - movement details, size, and whether they are owned by a player
* Bullets - owner and movement details
* (Possible additions)  Background and HUD to keep score
## Realistic goals/expectations for 3 weeks of work on the project
Depending somewhat on how bad the end-of-semester crunch is in my other classes, I don't think it is infeasible to complete the full functionality described above.  There is an HaxeFlixel Asteroids game I can reference for a lot of the core operations, though it is also almost completely void of documentation.
## (Optional) Concept image for game.
![Concept image](https://image.ibb.co/eAdTGQ/Untitled.png)
