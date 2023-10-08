# Pacman-Game

Steps to run the code:

step 1. HTML Structure:
   - The HTML file includes a basic structure with a <head> section defining the character set, viewport settings, and title.
   - There's a <style> section defining the CSS styling for the "container" element, which is a game area.

step 2. Buttons:
   - Two buttons are provided: "ADD PACMAN" and "PLAY GAME." They are associated with JavaScript functions "addPackman()" and "movPacman()" when clicked.

 step 3. JavaScript:
   - Several arrays (pacmen, x_pos, y_pos, x_vel, and y_vel) are initialized to keep track of multiple Pacman characters' properties.
   - The gravity variable is set to 1, representing a gravitational force.

step 4. addPackman() Function:
   - When the "ADD PACMAN" button is clicked, this function is called.
   - It creates a new Pacman character (<img>) with a random position (xpos and ypos) and random velocity (xvel and yvel).
   - The Pacman image is added to the "container" element, and its styling is set.
   - The character's properties are stored in arrays for future reference.

step 5. movPacman() Function:
   - When the "PLAY GAME" button is clicked, this function is called.
   - It iterates through the Pacman characters stored in the arrays.
   - It updates their positions based on their velocities and updates their images based on direction.
   - If a Pacman character reaches the boundaries of the container, its velocity is reversed, simulating bouncing.

step 6. setTimeout():
   - The movPacman() function is set to run repeatedly every 100 milliseconds using setTimeout(). This creates the illusion of continuous movement for the Pacman characters.

Future Implementation of code

Overall, this code creates a simple interactive game where you can add Pacman characters to the container and then start the game to see them move and bounce off the container boundaries. The Pacman characters change direction based on their position, giving them a playful appearance. The game continues until you close the browser tab or refresh the page.
