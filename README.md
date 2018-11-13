

# C project - Jerry Rush
This is a reference for setting up a  C project. It contains almost all of the attributes and flexibilities provided by C language.The code is designed in a modular way comprising of a total of 8 primitive header files which can also further be developed in a systematic way. This project is developed as a game. The player firstly inputs his / her name.The player controls Jerry (central character) chased by Tom. Meanwhile, jerry can collect coins and supprtive life along with overcoming the forwarding obstacles to him. The game gets much more interesting with time while jerry completes certain levels. However if the player's score is among the top 5, then it will automatically be included on the leader-board.
  
  
# Installation
- Platform : Windows 
- Libraries : SFML
- Tool : Microsoft Visual Studio 2017 
- In order to install the project the user must have the above mentioned pre-requisites. Here a short youtube video is attached on how to install and set up SFML libraries on Microsoft Visual Studio 2017 on a windows platform https://youtu.be/_9yem5dJt2E. Then finally  the user requires just only to download and keep all the files from the folder "Jerry Rush" from the link given on this GitHub page above in his or her respective project folder. 

# Documentation
- The codes of the project have been designed primarily among 6 header files and 2 cpp files associated with it.
- The execution of the project starts with the "Main.cpp" file and from there the execution branches out among the other header files.
- Here "Menu.cpp" file provides intra-linkage among the preeceding header files with it and also with the main.cpp .
- "Function_Prototype.h" contains the prototypes of all the functions used in the project. 
- "Game_Level_1.h" and "Game_Level_Two.h" cotains codes related with all the features of 1st and 2nd level respectively.
- Finally, "Game_Over.h" contains the functions which are used to stop the game , store current score on file , show leader-board etc. 
- All the images associated with the 1st level, 2nd level and menu are taken from files named "JR_imagefile.txt" , "JR_imagefile2.txt" and "Menu_file.txt" respectively.
- Similarly, the scores of the players are also stored in their associated files such as "highscore.txt" and then gets sorted.

# Features
- From the menu page a player can go and visit high score on the leader-board and obtain necessary instructions about various characters , obstacles and how to play a certain level.
- At the beginning , there is a theme-music-play which is related with the world famous cartoon show "Tom & Jerry".
- The player needs to enter his/her name at the beginning to start the first level.
- The player controls Jerry (chased by Tom) using key-board. 
- Jerry can move forward , jump upward  and go down or bent down by clicking the UP key and DOWN key respectively.
- The blue bird in the game is animated enemy which hinders Jerry from completing the levels. Also there are some subsidiary obstacles like box, stone and deep hole which Jerry must overcome to accomplish the level and gain points.
- By clicking the blue pause button , a player can pause the game in the current state.
- Similarly clicking the green resume button player can resume the game from current state.
- Also if a plyer does not want to continue the present level and wants to restart from the beginning ,then by clicking the red exit button, the player can go to main menu and start a new level again.
- In a certain level a player can increase the life by collecting the hearts . However maximum three hearts is allowed to be collected in a certain level.
- The player can accumulate more points by collecting the coins while running.
- After completing a certain distance , the player will automatically be promoted to the next level.
- If the score of the player is among those of the top five, then his or her name will automatically be included on the sorted leader-board.
- Finally the player can exit the game by clicking the exit button on the menu page.
 



 
