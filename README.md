# Vue3-Projects
A repository containing all the different pet projects I created using Vue3, with links to said projects provided where applicable.

- ### Navigate
  - <a href="Reaction-Timer-Game">Reaction-Timer-Game</a>
  - <a href="My-Planner">My-Planner</a>

## Reaction-Timer-Game

<a href="https://reactiontimergame.onrender.com">Visit my website here!</a>

A game based off of <a href="https://humanbenchmark.com/">humanbenchmark</a> that utilizes Vue3 that measures the player's ability to quickly click on a panel when it flashes to GREEN after a random period of time. The game has the player react 5 times, then returns the average of all 5 attempts and outputs to the player whether or not their attempt was above or below the average human's reaction time (273ms).

## My-Planner

A localized planner created with Vue router that allows for the user to create, modify, delete, and update projects that they wish to document. The project also utilizes a filtered navigation bar that allows for the user to display only certain types of projects (ex: only display completed or in progress projects). Unfortunately, due to the nature of the project allowing for total user control/administration, the project is not able to be hosted on a remote server. However, one can download and run the project themselves to view its full capabilites! 

<strong>NOTE: THIS PROJECT RELIES ON AN FAKE REST API RAN WITH THE Node.js PACKAGE 'json-server'. TO INSTANTIATE: </strong>
```
- Create two terminals that cd to the directory that contains the project.

- In one terminal, run the command 'npm run serve' to instantiate the server that Vue3 will run the project on.
  ex: http://localhost:8080
  
- In the other terminal, run the command 'json-server --watch data/db.json' to instantitate the false API.
  ex: http://localhost:3000
  
- After both terminals finish executing their respective commands, the project is live at the server Vue3 opened!
  ex: http://localhost:8080
```
