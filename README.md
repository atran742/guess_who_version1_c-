# guess_who_version1_c-
a custom guess who game (version 1)
Class game 

Private variables:

vector<string> board1;
Holds all the values imputed by the player 

vector<string> board2;
Hold all the values imputed by the player 

Int rounds;
Counts all the rounds being played;

String guess1;
Is the character the must be guessed in order to win 

String guess2;
Is the character the must be guessed in order to win 

Bool winner1;
Determines if there is a winner 

Bool winner2;
Determines if there is a winner 


Default constructor

game()
Initializes rounds variable to 0;

Public member functions

Void startGame()
Prints outs if players would like to play the game. Calls enterGame().
Preconditions: none
Post conditions: print statements are printed 

Void enterGame()
Asks players to enter how many characters they would like on their board. Gives each player a random character to guess. Calls playGame().
Preconditions: none 
Post conditions: statements are printed, and strings are added to vector/board 

Void play1()
Lets players ask questions and then removes certain characters from each players boards. Allows the player to guess which character their opponent has and determines if they win. 
Preconditions: none 
Post conditions: characters are removed from the board

Void play2()
Lets players ask questions and then removes certain characters from each players boards. Allows the player to guess which character their opponent has and determines if they win. 
Preconditions: none 
Post conditions: characters are removed from the board

playGame()
Switches between play1() and play2(), and determines if there is no winner(tie)
Preconditions: none 
Post conditions: ends program when game is finished

Void printBoard1()
Prints board 1. 
Preconditions: none 
Post conditions: board is printed

Void printBoard2()
Prints board 2. 
Preconditions: none 
Post conditions: board is printed

Bool isWinner1(string guess)
Determines if players guess matches with the character they need to guess in order to win.
Preconditions: needs a string value
Postconditions: returns a boolean value

Bool isWinner2(string guess)
Determines if players guess matches with the character they need to guess in order to win.
Preconditions: needs a string value
Postconditions: returns a boolean value




