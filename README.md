###########################
# Cube Crusher

Designed for students in/past Module 2, this project builds off of the basic Frontend and JS topics you've studied over the last 3 months.

# HTML
[index.html](./index.html) is the only HTML. It contains the canvas element where the game will be taking place.

# CSS
Used minimally. Everything is happening in Canvas

# JS

Base functionality for the game and the enchant.js library are included here. 

## Scenes
The 2 scenes, Main Menu and gameScene are here.
A GameOver Scene should be developed.

## Game Objects
Background, ball, paddle, block files are all here. Additional items like the various power-ups should also be implemented here.
The syntax follows the enchant js Class.create syntax where you're creating an object with a name and a initialization method that specifies the objects coordinates and sprite.
Currently, some functionality is split into the js/gameLibrary.js file and should be merged back into the corresponding gameObject file.

# JSON
### levels

Inside of the levels folder, you can create additional levels. In a JSON format, create an object that has a property called rows.

Rows should be an array of numbers.

Each number represents a different color when rendered into the game. 9 renders empty spaces.