Sequence 

Description: The project I created for my 15-112 term assignment is an online version of the card game sequence. I used sockets in order to create a server upon which three clients connect, representing the three players of the game. When running the multiplayer mode, players play the game against each other as they attempt to create a sequence or in other terms create a consecutive connection of five pieces in any direction. On top of the multiplayer capabilities, I also created a single player mode, which allows users to play against an AI, which has an algorithm for determining the best move to make. 

How To Run Project: Since this is a sockets game, one has to open up 4 terminal windows. Upon opening the terminal windows cd into wherever the files are stored. Next run the sequence_server.py file and click allow when a prompt appears. Next, on each of the remaining terminal windows, run sequence_client.py. Fortunately for those attempting to run the game, I include code which automatically updates the PORT number so the users do not have to worry about constantly changing that number.  

How to install libraries: In order to install libraries go to https://www.cs.cmu.edu/~112/notes/term-project.html and save the module manager link shown as a python file called module_manager. Then at the top of the python file you want the modules installed in type the following before the import call to the modules: 

import module_manager
module_manager.review()

In terminal the modules should begin to install the modules. Some libraries I have posted the link for the code which leads to how to download (for example pyaudio).