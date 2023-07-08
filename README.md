# PVZFovChanger
Simple program that makes changing pvz shooter games fov easier.
This program works by getting all current games through the Registry, and finding the pvz games installed, it will add those games to a list and display them to a selectable console. When a game is selected it will find the file that contains the FOV and wait for user input, once user input is given it will then write to the file using the StreamWriter class. If the game is open it will close it to make the changes then reopen. Please report any issues to me.
