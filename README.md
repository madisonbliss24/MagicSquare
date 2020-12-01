# MagicSquare_Java

This program asks the user for the name of a file
The user enters the name of a text file that's contents appear like

17 24 1 8 15 <br />
23 5 7 14 16 <br />
4 6 13 20 22 <br />
10 12 19 21 3 <br />
11 18 25 2 9 <br />

The program then reads the file into a 2D array and determines 
whether the matrix is a magic square (no repeating numbers, all diagonals, horizontal and vertical lines add up to the same number)

if the program is given a proper magic square then the output appears like so:

#################################################################################################### <br />
Enter a file to open: 
myfile.txt

The combination of numbers 

17 24 1 8 15 <br />
23 5 7 14 16 <br /> 
4 6 13 20 22 <br /> 
10 12 19 21 3 <br /> 
11 18 25 2 9 <br /> 

is a magic square of order 5. The magic constant is 65.
##################################################################################################

if the matrix given is not a magic square the output appears like this:

################################################################################################## <br />
Enter a file to open: 
myfile.txt

The combination of numbers 

17 24 1 8 15 <br /> 
23 5 7 14 16 <br /> 
4 6 13 20 22 <br /> 
10 12 19 21 3 <br /> 
11 18 25 25 9 <br /> 

is not a magic square.
##############################################################################################



