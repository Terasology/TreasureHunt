# TreasureHunt
Basic Treasure Hunt module, massive improvements coming

This module aims to create a treasure hunt for the player inside Terasology. As of now it is pretty small and has room for major improvements:

- Code reformating will be done in order to access player & chest locations more easily --> Done
- General code optimization and improvement, because as of now I use a "trick" to achieve what I want to do (it works, but is ugly)
- Will add a thread/scheduled task to refresh player location because ATM it's only loaded once --> Replaced by catching an event everytime the player moves. Sine the chest location is fixed anyway.
- Will add riddles instead of simple Player location and Chest Location
