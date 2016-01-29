# truthsOfPredation
Bloomberg coding challenge

Truths of Predatation 
Introduction
On planet Dorne in galaxy Harrenhal, there exist three types of animals: Wampa, Nexu and Tribble.
Wampa can eat Nexu, Nexu can eat Tribble, and Tribble can eat Wampa.
Dorne has N animals, numbered from 1 to N, which are each one of the 3 types.
A troll named Horda will tell you K clues about these animals. Each piece of information has one of the
two forms below:
1 X Y : this tells you that x and y are of the same type
2 X Y : this tells you that x can eat y
Being a troll, some of the clues given are false. The clue is false if it satisfies any of the three conditions
below, otherwise it's true:
X or Y is larger than N
The clue states X can eat X
The clue conflicts with a true clue before
Your task is to process all clues and detect the number of false clues.
Input Specifications
The first line will contain a number N ( 1 <= N <= 100 ) denoting the number of animals on Dorne and K
(1 <= K <= 100 )
denoting the number of clues Harda will provide. This will be followed by K lines, each with three positive
integers. The first number C (1 <= C <= 2) will tell you which type of clue this is, followed by X and Y (1
<= X,Y <= N).
Output Specifications
Your program will output a single integer denoting the number of false clues provided by the troll.
Sample Input/Output
Input
100 7
1 101 1
2 1 2
2 2 3
2 3 3
1 1 3
2 3 1
1 5 5
Output
3
Explanation
The 1st, 4th and 5th clues are false.
