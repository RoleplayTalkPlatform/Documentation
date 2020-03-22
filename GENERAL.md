# RoleplayTalkPlatform

## Overview
### [General Structure](#general-structure-1)
### [Libraries](#libraries-1)

## General Structure
### Description
We have 3 components you have to use in order to get a running system. Those components are:
* Frontend
* Backend
* Library in any programming-language
### Project Structure
Basically the library connects to the backend and updates the player-positions via REST.
The backend calculates the sound with volume and position in space for each player individually. 
The player connects via a browser to the frontend, where he can login with his own token. 
The frontend just gets the processed sound from the backend and gives it to the logged-in player.
The frontend just gets the processed sound from the backend and gives it to the logged-in player.

## Libraries
### Description
Libraries are implemented in any Game or Plugin for an existing Game. Our Goal is, to implement a library for as many programming-languages as possible. To archive that, we need your help! If you are good in any programming-language, just contact us to get an own repository and implement it in your programming-language.

### Already implemented libraries:
#### [Java Library](https://github.com/RoleplayTalkPlatform/Java-Library)