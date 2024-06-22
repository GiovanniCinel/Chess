# Project for Laboratorio di Programmazione course, Academic Year 2021-2022

## Authors: Cristian Bassotto, Giovanni Cinel, Gianluca Nordio

The program verifies and respects the official chess rules indicated on the following websites:
- https://www.scuolascacchipordenone.eu/le-regole.html
- https://www.scuolascacchipordenone.eu/le-mosse-speciali-.html
- https://www.scuolascacchipordenone.eu/scacco-scaccomatto-patta-.html

### Compiling the Executable
Download the file scacchi_definitivo.zip

Requirements:
- cmake

With CMake
1) Navigate to the Feild_Progect folder and from the terminal run $cmake -S . -B ./build
2) Enter the build folder ($ cd build)
3) Compile with $ make

### Running the Executable
4) Run $ ./Feild_Progect


### Project assignment
![Assegnamento_scacchiera_Pagina_1](https://user-images.githubusercontent.com/72708597/210579828-b075a0f8-8f02-408f-95d3-41b63e83e32d.jpg)
![Assegnamento_scacchiera_Pagina_2](https://user-images.githubusercontent.com/72708597/210579850-ac9de2d6-83c4-42b5-a0ec-620f2c138fbb.jpg)
![Assegnamento_scacchiera_Pagina_3](https://user-images.githubusercontent.com/72708597/210579859-e0d8192c-3949-459f-b859-9598a30cb5d3.jpg)
![Assegnamento_scacchiera_Pagina_4](https://user-images.githubusercontent.com/72708597/210579871-e75570b1-f158-4705-97d5-b480306b3b58.jpg)



Regarding the player versus computer mode, we have decided to include the following commands.

The possible combinations of letters for moves are:
- A1 B2: to move a piece from A1 to B2
- A1 B2 PP: to move a piece from A1 to B2 and propose a draw to the other player
- A1 MM: to display available moves for A1
- XX XX: to display the complete chessboard
- HE LP: to display the commands
- FF FF: to forfeit the game
The letter format does not affect the commands (a = A).

This message can also be viewed within the program by typing HE LP.
