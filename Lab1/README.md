This code uses sequential circuit one catch one by cout.
ALU control [0][1] decides the behavior of the operator(add or and slt)
ALU control [2][3] decides if input should be inverted or not.
SUB=A+(~B)  NOR=(~A)AND(~B)  NAND=(~A)OR(~B)
The last bits decide overflow.
