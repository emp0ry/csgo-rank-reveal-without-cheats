# CS:GO Rank Reveal without Cheats!

this is not a cheat, this just utilises the -netconport launch option which allows for applications to connect to the game's console and read and send console commands.

using this, i run the name and status commands to get the players in the current server and parse their rank information on csgostats.gg

![image_rankreveal](https://user-images.githubusercontent.com/64217088/235523644-dacf5c4f-a639-4b44-ba88-50c9c3b46d87.png)

## setup for main.py

- install the requirements: `pip install -r requirements.txt`
- add the launch option `-netconport 2121` to csgo
 
#### Inspired by this source code https://github.com/f0e/csgo-rank-reveal
