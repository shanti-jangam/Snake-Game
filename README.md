# Snake-Game
Snake is a classic game where the player controls a snake to collect food (pi) on a map. The snake grows longer with each food eaten. It moves in four directions, and the game ends if it hits the screen boundaries or itself. The goal is to survive as long as possible while collecting food and avoiding collisions.

Game Rules
• In this game, the snake itself is the main character.
• It should be able to move in four directions (up, down, left, right).
• Each time it eats food, its body would stretch.
• The food will appear in random places.
• The snake should not eat itself and when it does the game terminates.
• If the snake touches any four sides of the screen , the game terminates.

Requirements
• Only one player is allowed to play a game at a time
• Every time the program is run, the terminal would appear
• Every time the player eats a food, the snake stretches by size and when the snake
runs to own body or when it touches the screen , the program terminates.

Steps to Build a Python Snake Game
• Create the display window by using curses.
• The curses is a library that can be used to create text user interface application. It is
terminal controlled library i.e. the code written using curses can only be run
through terminal.
• Initialize the screen size and the screen refreshes for every 100 ms.
• Initialise the snake and the food.
• Every time the snake runs into the food the its body grows in length.
• The game terminates when the snake runs into its own body or when it runs into
boundaries of the screen.
