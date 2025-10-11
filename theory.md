### Introduction

Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors. <br><br>
1) Half Subtractor<br>
2) Full Subtractor
                     

###  1) Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, A (minuend) and B (subtrahend) and two outputs Difference and Borrow. The logic symbol and truth table are shown below.
<br>
<center>
<img src="images/halfsubtractorblock.png"  width="325" height="210"> <br> <b>Figure-1:Logic Symbol of Half subtractor</b><br>
      
<img src="images/Halftruthtable.png"  width="400" height="310"> <br> <b>Figure-2:Truth Table of Half subtractor</b></p> 
<br>

<img src="images/halfcircuit.png"  width="400" height="310"> <br>
      
<b>Figure-3:Circuit Diagram of Half subtractor</b></p> 
<br></center>
From the above truth table we can find the boolean expression.<br>
<center><b>Difference = A ⊕ B<br>
Borrow = A' B <br></b></center>

From the equation we can draw the half-subtractor circuit as shown in the figure 3.<br>

### 2) Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely A (minuend), B (subtrahend), and Bin (borrow-in) . It accepts three inputs: A (minuend), B (subtrahend) and a Bin (borrow bit)  and it produces two outputs: D (difference) and Bout (borrow out). The logic symbol and truth table are shown below.<br><br>
       <br>
<center><img src="images/fullsubtractorblock.png"  width="345" height="270"><br> <b>Figure-4:Logic Symbol of Full subtractor</b><br>
<img src="images/fulltruth.png"  width="400" height="310"> <br><b>Figure-5:Truth Table of Full subtractor</b></center>
  
<br>     

From the above truth table we can find the boolean expression.<br>
<center><b>D = A ⊕ B ⊕ Bin<br>
Bout = A' Bin + A' B + B Bin <br></b></center>

From the equation we can draw the Full-subtractor circuit as shown in the figure 6.
<br>
<center><img src="images/fullsubtractorcircuit.png"  width="600" height="310"> <br><b>Figure-6:Circuit Diagram of Full subtractor</b></p> </center>




