#CraftTime
A Minecraft server plugin to track playtime of users connected to the server.

##Plugin Idea
There are a number of possible use cases for this plugin:
- Calculating fair monthly fees for players based on server usage.
- Rewarding players based on the amount of time 
spent on the server
    - Lootbox every 1 hour played
    - A title (prefix) for the most amount of playtime out of any player that has
    connected to the server
    - New permissions based on how active a player is

##Todo
- Attach plugin to DB? (For storing elapsed time)
    - Does connection time only need to be pushed to DB on disconnect?
- Wait for connection then start timer (per player)