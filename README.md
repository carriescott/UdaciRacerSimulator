# Welcome to the One and only UdaciRacer Simulation Game

## Project Introduction

UdaciRacer is a racing game, which allows a user to race a simulated racer! This racing game runs as a Node application. Players can choose their racer and the track they want to race on. The strategy of the game is for each player to choose a pod racer they expect to win over a certain race track based on the pod’s characteristics (acceleration, handling, and top speed). 
A pre-built API creates the race selected by the players and returns a stream of information lasting the duration of the race, resulting in a final ranking of racers.


## Game Mechanics
Select a player and track, the game begins and you accelerate your racer by clicking an acceleration button. As you accelerate so do the other players and the leaderboard live-updates as players change position on the track. The final view is a results page displaying the players' rankings.

## Getting Started

In order to build this game, you need first need to clone this repo and then run two things: the game engine API and the front end.

### Start the Server (Game Engine API)

The game engine has been compiled down to a binary so that you can run it on any system. 

To run the server, locate your operating system and run the associated command in your terminal at the root of the project.

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux` |

If you are on an older OS and the above command doesn't run for you - or if you know that you are running a 32bit system - add `-32` to the end of the file name. For reference, here are the same commands but for a 32-bit system.

| 32 Bit Systems Only!  | Command to start the API                                     |
| --------------------- | ------------------------------------------------------------ |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx-32`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-32.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux-32` |

Note that this process will use your terminal tab, so you will have to open a new tab and navigate back to the project root to start the front end.

### Start the Frontend

First, run your preference of `npm install && npm start` or `yarn && yarn start` at the root of this project. Then you should be able to access http://localhost:3000.

Happy Racing!

