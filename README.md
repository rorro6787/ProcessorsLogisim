# Summary
This is an implementation in a hardware simulator of 3 different basic processors that could be able to run different peaces of code. The first one would be a basic single cycle processor, followes with another one with a much bigger set of instructionsm and we will finish with a little pipelined processor, capable of working on up to five instructions in parallel.
<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## How to use
- Download logisim from the following link: https://sourceforge.net/projects/circuit/  
- Do all the steps until you have oppened the simulator.  
- Click on "Archivo" - "Abrir..."  
- Choose wich one of the folders that represent the 3 different processor you want to open  
- Click on "IA43MIPS" - "IA43MIPS.circ"

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Simple Single Cycle Processor
To begin with we have an implementation of a really simple processor capable of using the set of instructions: j, halt, lw, sw, alu, addi and beq. With it you could write simple programs where you could manipulate the register bank, as well as the data memory and the value of the pc register as well as been able to do some basic arithmetic operations:
<p align="center">
   <img src="https://github.com/rorro6787/rorro6787/blob/main/Images/procesadorBasico.png" height="700" />
</p>

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Extended Single Cycle Processor
Now, we have an implementation of a more complex processor capable of using the set of instructions: j, halt, lw, sw, alu, addi, beq, andi, ori, lui, bne, bgtz, blez, jal, jr and rsublt. With it you could write more complex programs where you could manipulate the register bank, as well as the data memory and the value of the pc register as well as been able to do different arithmetic operations and control the flow of execution based on variuous branch conditions:

<p align="center">
   <img src="https://github.com/rorro6787/rorro6787/blob/main/Images/procesadorExtendido.png" height="700" />
</p>

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Extended Single Cycle Processor
Finally, we have an implementation of a really simple pipelined processor capable of using the same set of instructions as the first one shown. In functionality, both have the same ones, but in this case, we obtain a processor capable of work on different instructions at the same time, thanks to the pipelined registers that divide the processor in 5 independent sectors that can work on one instruction each:

<p align="center">
   <img src="https://github.com/rorro6787/rorro6787/blob/main/Images/procesadorSegmentado.png" height="500" />
</p>

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Technology Used
- Logisim

<hr style="height:2px;border-width:0;color:gray;background-color:gray">

## Team
- Emilio Rodrigo Carreira Villalta  
