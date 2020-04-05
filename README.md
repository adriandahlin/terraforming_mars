# Terraforming Mars
This is an app to manage resource production in the popular board game Terraforming Mars. Normally in this game, resource caches and production levels per player and per resource are recording using small beads placed on cards. There's a high risk of the table getting bumped and these beads being jostled, which effectively ruins the game. mars.py is a Python script run in the command line that keeps track of each player's name, current cache per resource, and production level per resource. Users can add their chosen player names and adjust the caches and production levels as the game progresses.

## Technical Explanation of the Script
mars.py uses object-oriented programming and centers around the class "Player". Each player has the following types of attributes:
- Terraform Rating (one)
- Current cache for each resource (six)
- Resource production rate for each resource (six)
