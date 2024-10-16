# Mini Minecraft 3D in p5.js
A basic 3D game inspired by Minecraft, created with p5.js in WEBGL mode. This project showcases basic concepts of 3D rendering, player movement, and procedural terrain generation using Perlin noise.

Demo

Features
3D Block World: Randomly generated blocks (Grass, Stone, Water) form the landscape.
Player Movement: Move around the world using W, A, S, D keys.
Procedural Terrain: Terrain heights generated with Perlin noise.
Camera Control: Use the mouse to adjust the view with orbitControl().

Controls
Movement: Use W, A, S, and D keys to move forward, left, backward, and right, respectively.
Camera: Use the mouse to pan, rotate, and zoom around the scene.
Reset View: Refresh the page to reset the world and camera.
Code Structure
index.html: Contains the basic HTML structure and links to the p5.js library.
sketch.js: Contains the game logic and rendering code.
Block class defines the blocks and their appearance based on type.
setup() initializes the world with a grid of blocks.
draw() renders the blocks and handles player movement and camera controls.
Block Class
The Block class has properties and methods to create and render different types of blocks:

Player Movement
The player’s position is controlled by the W, A, S, and D keys. Movement is updated in the draw() function with keyIsDown() checks.

To Do
Some possible extensions for the project:

More Block Types: Add more block types like Dirt, Sand, or Wood with unique properties.
Block Interaction: Allow block breaking and placing for more Minecraft-like gameplay.
Improved Terrain: Use 3D Perlin noise to create more realistic terrains.
Player Avatar: Add a 3D avatar model for the player.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Enjoy building your own Minecraft world with p5.js!






