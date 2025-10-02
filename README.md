# Tic-Tac-Toe-GUI-In-Python-using-PyGame
🎮 Tic Tac Toe GUI in Python (PyGame)  This project is a Graphical User Interface (GUI) based Tic Tac Toe game developed in Python using the PyGame library. The game provides an interactive 3x3 grid where two players can take turns marking their moves (X and O).
**Code Explanation:**
The code starts by importing the required libraries.
Then, it declares the global variables for storing the 'x' or 'o' value as character.
Next, it stores the winner's value at any instant of code.
To check if the game is a draw, there is a variable called draw that will be set to None when we are done with this function and then used in other functions later on in this program.
The next step is to set up some variables for width of the game window and height of the game window which will be 400 pixels wide and 400 pixels tall respectively.
It also sets background color of the game window to white (255, 255, 255).
The color of straightlines on that white board dividing into 9 parts is line_color = (0, 0, 0) while setting up a 3 * 3 board in canvas creates an empty array where each element has three spaces followed by two more elements which create nine squares on our tic tac toe board.
Lastly it initializes pygame window with pg.init() method before loading images as python object using pg image library methods such as load("modified_cover.png") , x_img = pg .image .load("X_modified."), y_img = pg
The code is a snippet of code that displays the game board in canvas.
The code declares global variables such as winner, draw, XO and line_color.
The code sets up the game window with width and height values.
The background color is white which is set to be 255, 255, 255.
The code starts by checking for the winner of the game.
If there is no winner, then it prints "XO's Turn" and sets a font object to print text on screen.
The code checks for winning rows and columns.
It also checks if there are diagonal winners in order to determine who won diagonally left or right.
The next part of the code starts with a function called check_win().
This function loops through all four possible combinations of winning rows and columns, which will be used later when determining who won diagonally left or right.
After this loop finishes, it determines whether XO has won by checking if board[0][0] == board[1][1] == board[2][2].
If so, then XO wins because they have three in a row horizontally (left-to-right) and two vertically (top-to-bottom).
The code is a basic game of tic-tac-toe.
The player who gets three in a row first wins the game.
The code begins by declaring variables for the board, winner, and draw.
The variable board will be used to store information about the current state of the game such as which rows and columns are won or lost.
The variable winner will store information about who has won the game so far.
The variable draw will hold whether or not there is a winner yet.
After declaring these variables, two functions are created: check_win() and draw_status().
These functions are called when it's time to check if someone has won or when it's time to update what is displayed on screen during gameplay
The code starts by defining a function called drawXO.
This function takes in two parameters: the row and the col of where to place an image on the screen.
The first parameter is defined as being 30 from the left margin, so for each row, we need to define what position it should be pasted at.
For example, if you wanted to paste an image over column 1, then you would set posx = width / 3 + 30.
The next line defines that XO will always be 'o' when it's not drawing anything else and 'x' when it is drawing something else.
Then comes a function called user_click which gets coordinates of mouse clicks and draws images accordingly based on those coordinates.
It also checks whether there is a winner or not before doing anything else with them (i.e., checking who won).
Lastly, reset_game resets everything back to how they were originally before starting up again with game_initiating_window().
The code is a program that plays Tic-Tac-Toe.
The code starts by defining the board, which is an array of three rows and three columns with the value None in each cell.
The game_initiating_window() function is called to start the game.
If you want to play again, you can call reset_game().
The while loop will continue until a user clicks on "Quit".
