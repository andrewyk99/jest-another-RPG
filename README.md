# Jest Another RPG
Jest Another RPG is a simple JavaScript games that has the user use the terminal to play a simple RPG (role playing game). The application makes use of Inquirer that gives the user their stats, their items, their health, and their enemy's health. The user then can choose whether to fight or use a potion when they like. The game will inform the player that they won if they defeat all the enemies or that they lost if their health reaches 0.

## Features
1. The user will be able to see their stats at the beginning of each round.
2. The user will see how many potions they have.
3. The user can user can decide to attack or use a potion.
4. The user can choose which type of potion they would like to use.

## User Story
I would like an application that lets me play a simple RPG. I would like the game to have character stats, potions, and allow me to decide what I would like to do at any point.

## Installation and Usage
### Clone Repository
* git clone https://github.com/andrewyk99/jest-another-RPG.git

### Install Dependancies
* run `npm i`

### Start Application
* run `node app.js`

## Tests
This application makes use of Jest to test a few of the JavaScripts functions, 'Enemy.js', 'Player.js', and 'Potion.js'. If you would like to run the tests yourself, after cloning and installing the code and dependancies, simply run `npm run test`. All the test files will be the folder labeled `__tests__`.

### Screenshots of Application
There is no live website of this application because the game is entirely ran in the terminal. To play, follow the instructions above.

![screenshot of game](./assets/images/game.png?raw=true "Game")
Screenshot of the game within the terminal

![screenshot of tests](./assets/images/tests.png?raw=true "Tests")
Screenshot of the tests

## Technologies Used
* JavaScript
* Node.js
* Inquirer
* Jest

## Contribution
Made by Andrew Kim