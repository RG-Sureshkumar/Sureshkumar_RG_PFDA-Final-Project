# Snake Game

## Repository
https://github.com/RG-Sureshkumar/Sureshkumar_RG_PFDA-Final-Project.git

## Description
This is a basiz snake game. There will be a snake character which collects food that is placed in random spots around the screen. The more food the snake collects the higher its score will be. The snake also becomes longer as it collects more food making it difficult for the player to move the snake without hitting any of the walls in the edges. If the snake hits and of the walls then the player loses and the game ends.

## Features
- Feature 1
	- I will use the pygame library to execute alot of the functions of the program.
- Feature 2
	- Keyboard input will be used to move the snake around
- Feature 3 
	- A random generator will be used to randomly generate the x and y coordinates of each food item. 
- Feature 4
    - There will be a loop that generates one food item once the previous food item has been eaten
- Feature 5
    - The food item will be considered eaten one the head of the snake and the food item are on the same x and y coordinates and then the loop of the food item will start again
- Feature 6
    - There will be a score counter at the end of the loop that increases by one each time the loop ends
- Feature 7
    - Each time the loop ends the length of the snake will also increase by a value of 1 
- Feature 8
    - The game will be considered done once the x and y position of the head of the snake is equal to the x and y positions the wall

## Challenges
- For this project one of the biggest skills that I am going to have to learn is how to use keyboard input to control a character
- I will also have to learn how to implement textures to create the ground and walls
- I will also have to read more about the pygame library to see what other pygame objects I could use to easily implement some features

## Outcomes
Ideal Outcome:
- The ideal outcome of this project is that I can create a snake character that can move around using keyboard inputs and collect food items that are placed around the screen. As the snake collects the food items the snake increases in length and the score increases by one. The game will end when the snake hits one the walls on the edges.

Minimal Viable Outcome:
- The minimal outcome is of the project is that there would be a snake character that can move around using keyboard inputs and collect food items around the screen. The game will end when the snake hits one of the walls on the edges. 

## Milestones

- Week 1
  1. Create the game screen and add color and textures to it
  2. Create the snake character and add color to it
  3. Create the food item and add color to it

- Week 2
  1. Add comands that allow the snake to move around the screen
  2. Create a random number generator that generates the x and y values of the food item so that it is placed a random place on the screen

- Week 3 (Final)
  1. Create a loop that generates a food item once the previous food item has been eaten, increases the score of the player, and increases the length of the snake
  2. Create an end condition that ends the game once the snake hits the walls on the edges