# B-Location
This is a 1.16.4 minecraft minigame plugin where the objective is to find and stand on a randomly designated block before the time runs out.
As this project is in open beta everything you see currently is subject to change.

# Useflow
1. Run '/blocation start'. This will assign every player a random block, which will be shown on the scoreboard. Any player that does not stand on their block within the specified amount of time will be eliminated until there is either one or zero players left.
2. Run '/blocation stop' to stop the game at any time.

# Installation
Download the jar from the latest release and move it to the plugins folder in your server. When the server starts it will automatically download the 'blocation-blockgroups.json' and put it in the correct position.

# Side Notes
* There is an alias for the 'blocation' command for easier use, it is 'blc'.
* At the beginning of every match all players will be teleported to the world spawn so please make sure it is a desirable location.
* This plugin is made with the Spigot API but it should work with most popular server apis.
