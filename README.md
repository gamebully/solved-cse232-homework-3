Download Link: https://assignmentchef.com/product/solved-cse232-homework-3
<br>
<ol>

 <li>Compute the clock period for the following clock frequencies.

  <ol>

   <li>50 kHz (early computers)</li>

   <li>300 MHz (Sony Playstation 2 processor)</li>

   <li>4 GHz (Intel Pentium 4 processor)</li>

   <li>10 GHz (PCs of the early 2010s)</li>

   <li>1 THz (1 terahertz) (PCs of the future?)</li>

  </ol></li>

</ol>




<ol start="2">

 <li>Trace the behavior of a level-sensitive SR latch for the input pattern in below figure. Assume S1, R1, and Q are initially 0. Complete the timing diagram for S1, R1 and Q, assuming logic gates have a tiny but nonzero delay.</li>

</ol>




<ol start="3">

 <li>Compare the behavior of D latch and D flip-flop devices by completing the timing diagram adding Q (latch) and Q (flip-flop) in below figure. Provide a brief explanation of the behavior of each device. Assume each device initially stores a 0.</li>

</ol>




<ol start="4">

 <li>FSMs with the following numbers of states, indicate the smallest possible number of bits for a state register representing those states:

  <ol>

   <li>4 8                         c. 9                         d. 23                       e. 900</li>

  </ol></li>

</ol>

<strong> </strong>

<ol start="5">

 <li>If an FSM has N states, what is the maximum number of possible transitions that could exist in the FSM? Assume that no pair of states has more than one transition in the same direction, and that no state has a transition point back to itself. Assuming there are a large number of inputs, meaning the number of transitions is not limited by the number of inputs? Hint: try for small N, and then generalize.</li>

</ol>




<ol start="6">

 <li>Draw a state diagram for an FSM with no inputs and three outputs x, y, and z. xyz should always exhibit the following sequence: 000, 001, 010, 100, repeat. The output should change only on a rising clock edge. Make 000 the initial state. Using the process for designing a controller, convert the FSM to a controller, stopping once you have created the truth table and derive the Boolean expressions.</li>

</ol>




<ol start="7">

 <li>A wristwatch display can show one of four items: the time, the alarm, the stopwatch, or the date, controlled by two signals s1 and s0 (00 displays the time, 01 the alarm, 10 the stopwatch, and 11 the date—assume s1s0 control an N-bit mux that passes through the appropriate register). Pressing a button B (which sets B = 1) sequences the display to the next item. For example, if the presently displayed item is the date, the next item is the current time. Create a state diagram for an FSM describing this sequencing behavior, having an input bit B, and two output bits s1 and s0. Be sure to only sequence forward by one item each time the button is pressed, regardless of how long the button is pressed—in other words, be sure to wait for the button to be released after sequencing forward one item. Use short but descriptive names for each state. Make displaying the time be the initial state. Using the process for designing a controller, convert the FSM to a controller, stopping once you have created the truth table and derive the Boolean expressions.</li>

</ol>