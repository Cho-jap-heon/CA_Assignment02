CA assignment 2:

first: addi $t0, $zero, 7   →  $t0 = 7
second:  addi $t1, $zero, 3   →  $t1 = 3
third: sub  $t2, $t0, $t1   →  $t2 = 7 - 3 = 4
Convert the following instructions to hex machine code,
write them into memfile.dat, and simulate using your
MIPS single-cycle datapath.
 
To verify, the register addresses are:
  $t0 = 8,  $t1 = 9,  $t2 = 10


--- Start Simulation ---
PC: 00000000 | Result:          7 (Expected 7)
PC: 00000004 | Result:          3 (Expected 3)
PC: 00000008 | Result:          4 (Expected 4)
datapath_tb.v:140: $finish called at 55000 (1ps)
