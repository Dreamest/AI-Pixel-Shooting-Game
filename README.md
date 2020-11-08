# AI-Pixel-Shooting-Game

This is a pixel based shooter game simulation, in which two teams fight against each other.
The simulation runs in turns, where in each turn, each NPC gets to move one tile or shoot.

The game randomly generates rooms, and then using the A* algorithm creates paths between all rooms.
Each NPC starts with 100 HP and 10 bullets, as well as a variant to their gun, they can either shoot twice in a turn, or shoot stronger bullets.

The NPCs follow a decision tree to determine what action to take next, then follow the A* algorith in order to fulfil their task.

![Decision Tree](https://i.ibb.co/Ybqtd9v/Whats-App-Image-2020-11-08-at-22-04-10.jpg)
