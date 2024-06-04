# ENGR103Game
Engineering 103 Final Project

Game Description

For my game I plan to make a similar structure to guitar hero. The program will have 3 unique states:
•	Home – Explains the rules of the game and allows for selection of a variety of songs.
•	Playing – plays the chosen song.
•	End – Displays score and prompts user if they want to continue. 
The game works by treating both sides of the circuit as different sets of pixels. On either side the lights will turn on and off in a descending fashion. When the light reaches the bottom of the board, the user must press the appropriate button depending on the side of the board. Players will be scored on the accuracy of their inputs and a corresponding voice message will play. The difficulty of the game is determined on whatever the song the user chooses. 
Inputs:
•	Left Button-Used to play the note associated with the left LED string.
•	Right Button- Used to play the note associated with the right LED string.
Outputs:
•	Left LEDs – Illuminates a single pixel descending towards the bottom of the board on the left side.
•	Right LEDs – Illuminates a single pixel descending towards the bottom of the board on the right side.
•	Speaker – Plays notes in a song according to pitch and duration. Pitch will be determined using the GenerateMidi(); example used in lecture.  

