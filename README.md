# ChessProblem
The problem is to find all unique configurations of a set of normal chess pieces on a chess board with dimensions M×N where none of the pieces is in a position to take any of the others. Assume the colour of the piece does not matter, and that there are no pawns among the pieces.
Write a program which takes as input:
•	The dimensions of the board: M, N
•	The number of pieces of each type (King, Queen, Bishop, Rook and Knight) to try and place on the board.
As output, the program should list all the unique configurations to the console for which all of the pieces can be placed on the board without threatening each other.
When returning your solution, please provide with your answer the total number of unique configurations for a 7×7 board with 2 Kings, 2 Queens, 2 Bishops and 1 Knight. Also provide the time it took to get the final score. Needless to say, the lower the time, the better.





Examples

Input: 3×3 board containing 2 Kings and 1 Rook.
Output:
K	 	K		K	 	 		 	 	K		 	R	 
 	 	 		 	 	R		R	 	 		 	 	 
 	R	 		K	 	 		 	 	K		K	 	K
 

Input: 4×4 board containing 2 Rooks and 4 Knights.
Output:
 	N	 	N		 	N	 	N		R	 	 	 		 	 	R	 
 	 	R	 		R	 	 	 		 	N	 	N		 	N	 	N
 	N	 	N		 	N	 	N		 	 	R	 		R	 	 	 
R	 	 	 		 	 	R	 		 	N	 	N		 	N	 	N
																		
 	R	 	 		 	 	 	R		N	 	N	 		N	 	N	 
N	 	N	 		N	 	N	 		 	 	 	R		 	R	 	 
 	 	 	R		 	R	 	 		N	 	N	 		N	 	N	 
N	 	N	 		N	 	N	 		 	R	 	 		 	 	 	R

