Multiplier and Divider (Sequential Circuits)
---
Screenshots of the circuits are provided. 

Assignment guidelines: 

Question 2: *Multiplication* (8 marks)

Create a sequential circuit that implements an 8 bit unsigned multiplier. Your circuit should have
RESET signal to signal that two 8 bit inputs A and B are ready to multiply. Your circuit should
also provide a DONE signal that goes high when the 16 bit result is ready. You may use anything
you like from the default Logisim library (e.g., wiring, gates, plexers, memory), but you should only
use one Adder circuit from the Arithmetic part of the library. Use 8 bit pins as input and attach
probes (see wiring) to your input to display the value in decimal. Likewise attach a probe to your
16 bit output. Bonus: receive one extra mark if your solution is correct and uses only a single 8 bit
adder.

Question 3: *Division* (8 marks)

Create a sequential circuit that implements 8 bit unsigned division. Since the shift register included
in the library only shifts right, you will certainly want to create a sub-circuit that implements a
left shift register (you can do this by swapping the order of the inputs). Again, you may use any
circuits you like from the default library, except that you should only use one subtraction circuit
from the Arithmetic part of the library. Implement RESET and DONE signals as per the previous
question. Bonus: receive one extra mark if your solution is correct and you use only a single 8 bit
subtraction circuit.
