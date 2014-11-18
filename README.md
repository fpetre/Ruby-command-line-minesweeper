Ruby-command-line-minesweeper
=============================

Minesweeper implemented in ruby ran via command line

How to play: 

Have ruby installed then from the command line write "ruby minesweeper.rb (name of text file to be used for save)".

If you dont give the name of a text file it will automatically create a file called save.txt. 

If given an empty file it will start a new game and save to that file. if the file has a save on it, 
it will load the game from the save. 

Commands: 

To flag or reveal a position type "f" or "r" followed by the coordinates.

example: f 2,3

To save type s by itself.

To exit use ctrl + c

Features:

-Implemented save feature by storing game state as YAML in a text file

-Uses breadth first search when searching for adjacent tiles

