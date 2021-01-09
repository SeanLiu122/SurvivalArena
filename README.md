# Result
* Youtube video to show around the project: <br>
[![Youtube thumbnail image](http://img.youtube.com/vi/9WJnajEbwKg/0.jpg)](https://youtu.be/9WJnajEbwKg, "Unreal Engine Project Demo")


# SurvivalArena
A simple survival game that is powered by Unreal Engine 4 and programmed in Blueprint. A simple game project in a top-down view that is based on the winning condition to complete each spawned wave, and there are 5 waves in total (easy to debug); each wave spawned a few enemies to chase and attack the player if they are in their detection radius; to clear each wave: the player had to kill all the bots on the level. Also included a player controller character: a Knight or Mage (Mage is a child of Knight-to share common features and consistency); but the player must have to manually swap it in the game mode, did not implement this feature like the real video game that allow the player to choose their favorite class/job in it. A controller character attacked with a unique assigned attack animation with the used of Animation Blueprint; for example, a Knight character plays the melee attack animation (two different swings), and a Mage character plays the casting spell animation when she attacked.

Implemented a basic AI/bot that can be wandered by the used of Navigation Mesh Bounds Volume, chased and attacked the player if they are in their attacked range. However, all the bots in the game are reusing the character classes because of consistent use. Designed and detailed the only one level (not enough time) in this project with the scene of fantasy ruined castle, and with the used of Landscape mode. Later on, I expanded the game to have some interfaces: main menu, winning screen, death screen, and scoring HUD; health pick-up systems; and audios.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for testing and gameplaying purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
This project was packaged for Windows 64-bit. Better to download and run it on a Windows OS 64-bit.

### Installing
Clone the project with the git tool, and then launch the Survival.exe file. 

## Acknowledgments 
* This project was for the Udemy course: "Unreal Engine 4: How to Develop Your First Two Games" section 3, and instructed by Christopher Murphy.
  * Link: https://www.udemy.com/unreale4/learn/v4/overview
* Assets are obtained from Infinity Blade's Weapons and Grass Lands packs in the Unreal Engine Marketplace. 

### Need to Fix
* For some reason there is a bug in a Mage character bot that sometimes she will die if the player successfully killed her, but sometimes she won't and jump back to attack the player. 
