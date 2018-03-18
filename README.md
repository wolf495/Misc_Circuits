# Misc_Circuits
The following is an assortment of circuits I've created  using a program called 'Logism' which can be downloaded here 

http://www.cburch.com/logisim/download.html 
OR
if on windows I included the executable

*to interact with the circuits, click the pointing hand in the top left of the Logism window*


Cominatorial - In this circuit, I check the validity of dates (in binary). 
              EX) When the following is entered... 00  0001   11101 .... it means 'not leap year, February, 29'
                        and the 'Valid' LED is unlit (grey) because that is not a valid date. however the day 
                        '11100' (28)  makes the 'Valid' LED lit (red) because it is a valid date

flipflop - In this circuit, I create a counter. Opening the 'Counter' circuit, it must be reset first, by 
          clicking the Reset button, and flipping it back off, and clicking the clock buton increments the number in 
          binary. This circuit uses 2 other circuits i created, the Register, and the FlipFlop.

gates - In this circuit, I create a display for numbers 0-3, which can be changed using the boxes next to the 
        left of the circuit.

RockPapSci -  In this circuit I create a a simulation of rock,paper,scissors by comparing the hands thrown 
              and displaying if player 1 or player 2 has won (indicated by RED in the LED)

tictactoe -   In this circuit, I mimic a toc-tac-toe board, and i check to see if a row of 1's or 0's matches 
              a winning pattern. If a row exists, an LED is lit to RED to signal a player has won
