# Game Proposal

## Overview
My game is called Finger Skate, the object of the game is to skate down the street avoiding obtacles and get to the bottom of the hill. The controller will be a finger skateboard. To turn in the game the player leans the same way on the finger board and to jump the player simply lifts their fingers off the skateboard and put them back on. 

## Core game mechanics
The core game mechanics will be avoiding obstacles while skating down a hill. The player will avoid obstacles by either navigating around them by moving horizontally or by jumping over them.

The runs will be timed so the goal of the game is to reach the bottom as fast as possible. There will be gold silver and bronze times to aim for. Obtaining medals could unlock new outfits or clothing items. 

There will be power-ups which help the player in different ways such as speed boost to get to end faster or jump boost to make it easier to jump over obstacles.

## Other potential ideas
Another idea I had was to have a joystick on the controller which would be used to jump and do tricks which would give you points. If this was included then a seperate game mode should be made where the goal is to get a high score rather than a fast time.   

# Controller Proposal

## Research
I plan to use an MPU-6050 to detect which way the player is leaning on the board. An MPU-6050 combines a gryoscope with with an accelerometer so I decided to research some controllers that used either of these parts. I found a game called Skyboard https://wdebowicz.itch.io/skyboard which uses a smartphone as an accelerometer. It uses the accelerometer to control the movement of the player which is exactly what I want to do. Another game called Slap Friends http://www.slapfriends.com/ uses lightweight acceleremoters to control the arms of the characters in the game to slap the other player. 

## Description
The main part of my controller will be the finger board which will have the MPU-6050 attatched to it. This will be used to conrtol the movement of the character, the player leans left or ight to move the character in that direction. To jump the player leans backward. A stretch goal would be to add a Joystick which would be used to do tricks and different grinds.


## Design 
![controller design](https://github.com/JonnyMarx98/comp140-gam160-game/blob/master/controller%20design.PNG)
