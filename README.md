# Logic-Circuits-Lab-Project

- project has 3 parts.
- project descriptions:

## 1. Calculator
In CPUs, there is a specific component for computation called “Arithmetic Logic Unit” (abbreviated
to ALU). You are asked to implement a simple ALU which performs the four common operations
(Add, Subtract, Multiply, Divide).
The component takes two 4-bit number, and a 2-bit number for mode which identifies the desired
operation. Suppose all numbers are in the 2’s complement form, except for “divide” operation. For
“divide” operation, suppose the numbers are unsigned.
The component outputs an 8-bit number as the result of the operation. If the operation was “divide”,
the first four bits show the multiplicand and the last four bits show the remainder.
The component also outputs four flags. 

<p align="center">
		<img src="https://user-images.githubusercontent.com/96329489/182360896-b90771a4-fea3-4d3c-8ed8-83194a5a95e4.png" />
</p>




## 2. Clock
Design a clock using 6 seven-segments. Note that you can set your clock using binary inputs for hour,
minute and second. For example, if you set the input of your hour part as 10010 and then run your
design, hour should start at 18 and then continue counting.

<p align="center">
		<img src="https://user-images.githubusercontent.com/96329489/182361412-a0e3c485-0ee1-4dd4-8750-37d25b07f292.png" />
</p>



## 3. Name block
Through use of different kinds of segments, you should design a block which will represent your name.
At first all of the segments are off and after 5 seconds the first letter of your name is shown. This
sequence continues until all of the letters are on, then you name will blink until end of the day.

<p align="center">
		<img src="https://user-images.githubusercontent.com/96329489/182361877-977cad2b-1942-4bb7-bfbb-6966e1bae6d6.png" />
</p>

