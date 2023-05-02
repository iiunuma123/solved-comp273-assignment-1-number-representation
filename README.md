Download Link: https://assignmentchef.com/product/solved-comp273-assignment-1-number-representation
<br>



1           Number Representation

Complete the table below. You must show your work to get full credit for an answer.

<table width="0">

 <tbody>

  <tr>

   <td width="67">Decimal</td>

   <td width="221">Binary</td>

   <td width="96">Hexadecimal</td>

  </tr>

  <tr>

   <td width="67">-243</td>

   <td width="221">give 16-bit signed representation</td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="67">728</td>

   <td width="221">give 16-bit signed representation</td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="67"> </td>

   <td width="221">1101.0111 (unsigned)</td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="67"> </td>

   <td width="221">11011100 (unsigned)</td>

   <td width="96"> </td>

  </tr>

  <tr>

   <td width="67"> </td>

   <td width="221"> </td>

   <td width="96">7D.8</td>

  </tr>

  <tr>

   <td width="67"> </td>

   <td width="221"> </td>

   <td width="96">1B5</td>

  </tr>

 </tbody>

</table>

<h1>2           Floating Point Number Representation</h1>

<ol>

 <li>Represent -76.678595 as an IEEE single precision floating point number (binary andhexadecimal).</li>

 <li>Represent 19.459931 as an IEEE single precision floating point number(binary andhexadecimal).</li>

 <li>Add the signed binary fixed point versions of the above two floating numbers usingbinary arithmetic and report your answer, showing your working.</li>

</ol>

You must show your work to get full credit.

3           Boolean Algebra

Assume that <em>F </em>is a Boolean function, as defined below, and all the other Boolean variables are inputs. Derive and give:

<ol>

 <li>The truth table, ii. A sum of products expression for <em>F </em>that is minimized.</li>

</ol>

iii. A product of sums expression that <em>F </em>is minimized. By “minimized” we mean an expression that cannot be further simplified while retaining its form (sum of products or product of sums).

<ul>

 <li><em>F</em>(<em>A,B,C,D</em>) = (<em>A </em>+ <em>B </em> <em>D</em>) · (<em>C </em>· <em>B </em>· <em>A </em>+ <em>C </em>· <em>D</em>)</li>

 <li><em>F</em>(<em>W,X,Y,Z</em>) = (<em>W </em>+ <em>X</em>)(<em>ZY </em>+ <em>X</em>)</li>

 <li>                                               4           Circuit Design</li>

</ul>

4.1           Universal Gates

A NAND gate or a NOR gate is a universal logic gate, because it can be used to construct all other logic gates. What is the minimum number of two input NAND gates required to

implement the following Boolean expression <em>F</em>(<em>X,Y,Z,W</em>) = (<em>X </em>+ <em>Y </em>) · (<em>Z </em>+ <em>W</em>), where <em>X,Y,Z </em>and <em>W </em>are inputs? Explain your reasoning. One you have figured out the minimum number of required NAND gates, draw the circuit in <em>Logisim </em>using only NAND gates and test it. The TAs should be able to change the logical values of the inputs while obtaining the correct output.

4.2           Parity Counter

You are asked to design a 4-to-3 parity counter. Such a circuit has 4 input bits, <em>A</em>, <em>B</em>, <em>C</em>, <em>D </em>and 3 output bits <em>F</em><sub>2</sub>, <em>F</em><sub>1</sub>, <em>F</em><sub>0</sub>. The value that the circuit outputs is the number of its input bits that are set to 1. For example if the input is 1010, then the circuit will output 010 (which is the binary representation of 2 as the unsigned 3-digit binary number <em>F</em><sub>2</sub><em>F</em><sub>1</sub><em>F</em><sub>0</sub>). Similarly, if the input is 1111, then the output will be 100. Consider <em>F</em><sub>2 </sub>as the highest order bit of the result and <em>F</em><sub>0 </sub>as the lowest order bit.

<ol>

 <li>Construct the truth table for this circuit.</li>

 <li>Write down the Boolean expressions for each of the three outputs in sum of productsform. Now, simplify each expression using the laws of Boolean algebra to derive minimized sum-of-products forms.</li>

</ol>

<ul>

 <li>Design this circuit in <em>Logisim </em>and test it. The TAs should be able to change the logical values of the inputs while obtaining the correct output.</li>

</ul>

4.3            Full-adders and half-adders (20 marks)

What is the minimum number of full-adders and half-adders that are needed to count the total number of ones in an unsigned 7-bit binary number <em>A</em><sub>6</sub><em>A</em><sub>5</sub><em>A</em><sub>4</sub><em>A</em><sub>3</sub><em>A</em><sub>2</sub><em>A</em><sub>1</sub><em>A</em><sub>0</sub>? You are allowed to use only full-adders and half-adders in your solution. You must show your work to get full credit. Draw the corresponding circuit diagram in <em>Logisim </em>and test it. For this you are allowed to use the built in “adder” module in logism-evolution, i.e., you don’t have to first build an adder from simpler gates.