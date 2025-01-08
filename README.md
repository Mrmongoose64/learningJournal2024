# learningJournal2024
2024 Programming Learning Journal

This learning journal will detail the process of creating four programming tutorials, and a game prototype to demonstrate them in action. </br>

The following are the topics my tutorials will be based on:

1. Main Menu
2. Timer System
3. Random Sound Effects
4. Pickup Counter

## 2024-10-22

I created a basic main menu with Play, Options and Quit buttons. I took screenshots of the steps I went through to produce it, but I might make some modifications later on. I initally loaded the scenes asynchronously, but changed this after finding out that doing so may cause issues in larger projects.<br>

I used tutorials by [Rehope Games](https://www.youtube.com/watch?v=DX7HyN7oJjE) and [Brackeys](https://www.youtube.com/watch?v=zc8ac_qUXQY) to help me.

## 2024-10-29

I added a "Return to Main Menu" button to the Options menu and took any necessary screenshots. I wrote the tutorial, which consists of 17 steps, each accompanied by at least one screenshot. I faced no real issues, but I did retroactively add some comments to my two scripts.<br>

I found a tutorial by [Game Dev Beginner](https://www.youtube.com/watch?v=HmHPJL-OcQE) that I plan to use to assist me when creating my next tutorial, a timer system. I also created a blank Unity project that I'll be using for the demo.

## 2024-11-05

I used the aforementioned tutorial to help construct my countdown timer system. The original used a legacy text object, so I had to do some further research to find out how the same could be done with a TextMeshPro. After making any necessary adjustments, I also taught myself how to import new fonts to Unity, something I've included in this tutorial. I took all the screenshots I needed, added descriptive steps and finished my second tutorial.

## 2024-11-12

I began making a randomised sound effect system for in-game footsteps. I've yet to complete this, as I'm struggling with playing sound while the player moves. I'm also unable to use a Unity feature to randomise the footstep sounds, as the computers on-site have an older version of the engine. I'll probably complete the bulk of it on a newer version at home.

## 2024-11-26

I changed my mind on making the randomised sound effect system in a newer version. Instead, I worked in the same version as my other tutorials and managed to create something that achieves a similar effect. There were initially some minor audio issues when making small movements, but I was able to fix these by only stopping the audio playback when the scene was silent.<br>

This was an especially difficult tutorial demo to complete, as I had to piece together different bits of code from various Unity forums, while also improvising during my bug fixing process.

## 2024-11-30

I took screenshots of my randomised sound effect system, and wrote the tutorial for it. Despite my aforementioned struggles, the tutorial ended up being the shortest of the three I've completed so far.

## 2024-12-03

I began work on the prototype project, adding in the timer system and main menu. I also made some modifications to the menu tutorial after discovering that I missed one of the steps initally (putting the scenes into build settings).<br>

Once I complete the pickup counter and tutorial, I'll add it to the prototype and be left with a basic game that requires the player to pick up a certain number of objects within a limited amount of time (potentially one minute). The game will be 2D, but I've yet to decide whether I want it to be top-down or styled more like a platformer.

## 2024-12-10

I started creating a pickup counter, largely focusing on the player's movement and the system that tracks how many pickups of each category are collected. Creating a robust movement system took some time, as I had to heavily modify my pre-existing code in order to normalise the magnitude of the player. This was done to ensure that the player wouldn't move faster when going diagonally, an issue found in a number of games that often gets exploited by speedrunners.<br>

I'm using a tutorial by [Alexander Zotov](https://www.youtube.com/watch?v=8v83ThB_oXQ) for the pickup counter, and I used an old movement system I coded as a foundation for the one in this prototype.

## 2024-12-17

I finished my pickup counter, which I'll now be able to add to my prototype. I also slightly changed the movement system to use physics instead of transforms, as this improves the functionality of collisions (e.g. when the player hits a wall). This isn't necessary in the pickup counter tutorial, but it's a better script that I'll be using in my prototype anyway. I've taken all the screenshots I need, and I'll compile them into my fourth and final tutorial.

## 2024-12-23

I wrote the tutorial for the pickup counter, thus completing all four of them. Each tutorial had the following number of steps:
* Main Menu - 18
* Timer System - 12
* Random Sound Effects - 9
* Pickup Counter - 13

## 2025-01-06

I added the pickup counter and random sound effect system to the prototype (although I've yet to implement the latter), and started developing the actual game. My idea was to have a series of maze-like levels, where the player has to collect every pickup before the time runs out. I was able to create this relatively quickly, but I did initially struggle with the code for switching scenes. I'm using the same scripts in every level, so I had to use the current scene's index as a variable, which took a while to figure out.

## 2025-01-07

I enabled the functionality of the random sound effect system. I made the footstep sounds myself last year during Game Production, by tapping on an electric heater and recording the audio. I also made some modifications to the resolution of the game, as I was experiencing issues when testing in my screen's native resolution. Despite not needing a build for this module, I wanted to make sure that it'd work anyway.<br>

I recorded myself playing through the game, and spent some time editing the footage to create an in-depth video demo that details its functions. I've uploaded the project files to a new GitHub repository, and I'll soon gather everything into one place, ready for submission.
