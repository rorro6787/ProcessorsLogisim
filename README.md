# Summary
This is an implementation in a hardware simulator of 3 different basic processors that could be able to run different peaces of code. The first one would be a basic single cycle processor, followes with another one with a much bigger set of instructionsm and we will finish with a little pipelined processor, capable of working on up to five instructions in parallel.
<hr style="height:2px;border-width:0;color:gray;background-color:gray">


## Simple Single Cycle Processor
To begin with we have an implementation of a really simple processor capable of using the set of instructions: j, halt, lw, sw, alu, addi and beq. With it you could write simple programs where you could manipulate the register bank, as well as the data memory and the value of the pc register as well as been able to do some basic arithmetic operations:
<p align="center">
   <img src="https://github.com/rorro6787/rorro6787/blob/main/Images/procesadorBasico.png" height="700" />
</p>

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Extended Single Cycle Processor
Now, we have an implementation of a really simple processor capable of using the set of instructions: j, halt, lw, sw, alu, addi, beq, andi, ori, lui, bne, bgtz, blez, jal, jr and rsublt. With it you could write more complex programs where you could manipulate the register bank, as well as the data memory and the value of the pc register as well as been able to do different arithmetic operations and control the flow of execution based on variuous branch conditions:

<p align="center">
   <img src="https://github.com/rorro6787/rorro6787/blob/main/Images/procesadorExtendido.png" height="700" />
</p>

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Longest Word Searching Algorithm
Using this Structure is very easy to create an algorithm that in any other structure would have an inimagible computation cost, but in this case with a more afordable cost. Basically, what this backtracking algorithm would do is: given an array of letters, return the longest string that can be formed doing any type of permutations to the original string and that it that is already inserted in the tree.
For example, if the tree had these words inserted -> [layer lan lies alies] and we are given the next set of letters -> "lseias", the algorithm should return the string "alies". In the source code the algorithm appears with the name of longestWord.

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Technology Used
- C

## Team
- Emilio Rodrigo Carreira Villalta
