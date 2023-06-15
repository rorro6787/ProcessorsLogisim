# ArrayTreeDictionary
This is an implementation in a hardware simulator of 3 different basic processors that could be able to run different peaces of code. To begin with we have an implementation of a really simple processor capable of using the set of instructions: j, halt, lw, sw, alu, addi and beq. With it you could write simple programs where you could manipulate the register bank, as well as the data memory and the value of the pc register as well as been able to do some basic arithmetic operations:
<p align="center">
   <img src="https://github.com/rorro6787/rorro6787/blob/main/Images/procesadorBasico.png" height="500" />
</p>
<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Atributtes of the DataStructure
The DataStructure itself is a pointer to an array of 26 nodes (1 for each letter in the alphabet) that will store 3 things: first of all, a boolean value that would clarify if the letter is being used and another one that would tell if that letter is the end of a word. A part of that each node would store a reference to another array of 26 nodes.
This way is really easy to decide if a word is stored or not in the structure. You only need n steps to decide if we already included that word (being n the length of the word).

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Longest Word Searching Algorithm
Using this Structure is very easy to create an algorithm that in any other structure would have an inimagible computation cost, but in this case with a more afordable cost. Basically, what this backtracking algorithm would do is: given an array of letters, return the longest string that can be formed doing any type of permutations to the original string and that it that is already inserted in the tree.
For example, if the tree had these words inserted -> [layer lan lies alies] and we are given the next set of letters -> "lseias", the algorithm should return the string "alies". In the source code the algorithm appears with the name of longestWord.

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Technology Used
- C

## Team
- Emilio Rodrigo Carreira Villalta
