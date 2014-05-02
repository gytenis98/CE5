CE5
===
#PART 1

#####addi $S0, $0, 44 (assigns 44 to register S0)
#####addi $S1,$0,-37 (assigns -37 to register S1)
#####add $S2,$S1, $S0 (Adds S0 and S1 together and stores it in S2)
#####sw $S2, 0X54($0) (stores S2 value in the memory named x54)

#PART 2

#####addi $S0, $0, 44     --->0X2010002C
#####addi $S1,$0,-37      --->0X2011FFDB
#####add $S2,$S1, $S0     --->0X02119020
#####sw $S2, 0X54($0)     --->0XAC120054


![alt tag](https://raw.githubusercontent.com/gytenis98/CE5/master/Capture1.JPG)
