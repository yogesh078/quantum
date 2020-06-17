# Chocolate distribution optimization problem
Problem statement:<br>
Optimize chocolate distribution among students by a teacher with minimum round trips between the chocolate boxes and seats.

Chocolate Boxes
-----
* Each chocolate box has 4 sections as shown below to put 1 chocolate in each section. These are indicated as TL, TR, BR and BL.

  ![Chocolate Box Layout](https://github.com/yogesh078/quantum/blob/master/assets/CBLayout.png?raw=true)

* Available boxes with chocolates already filled.

  ![Chocolate Box filled](https://github.com/yogesh078/quantum/blob/master/assets/CBFilled.png?raw=true)

* Above are the different types of boxes available that have chocolates already filled.
  * c1 = Hersey’s Kisses
  * c2 = Bournville
  * c3 = Kit Kat
  * c4 = Reese’s Cups
  
Classroom seating arrangements
-----
 &nbsp;&nbsp; ![Classroom Layout](https://github.com/yogesh078/quantum/blob/master/assets/CBLayout.png?raw=true)

* S1, S2, S3… Sn denotes seats.
* S1 (c1) means student at seat S1 needs chocolate c1 (Hershey’s Kisses)
* Seats with no chocolates present means students are absent for the day and no chocolates need to be distributed. i.e S17
* P1, P2, P3… Pn are different positions that teachers can stand and distribute chocolates.

Constraints
-----
* Teacher can carry only 1 box at a time for 1 trip.
* When the teacher is standing at a position, chocolates can only be distributed as per the sections present in the chocolate box i.e. if teacher is at position P1, then S1 can get chocolate from TL section, S10 from TR, S11 from BR and S2 from BL section.
* Teacher can only position facing toward the top to the setup i.e. facing towards the “Classroom” word and cannot rotate.

Expected Solutions
-----
Solution 1

 &nbsp;&nbsp; ![Solution1](https://github.com/yogesh078/quantum/blob/master/assets/Solution1.png?raw=true)

 &nbsp;&nbsp; ![Solution1 Steps](https://github.com/yogesh078/quantum/blob/master/assets/Solution1Steps.png?raw=true)

* The students who get chocolate with each trip are highlighted in the same color as Sr# column.
* Based on the above approach, total round trips that are required to complete the distribution on chocolates = 7. (These 7 round trips are highlighted with different colors and steps are written with same color in Sr# column)

Solution 2

 &nbsp;&nbsp; ![Solution2](https://github.com/yogesh078/quantum/blob/master/assets/Solution2.png?raw=true)
 
 &nbsp;&nbsp; ![Solution2 Steps](https://github.com/yogesh078/quantum/blob/master/assets/Solution2Steps.png?raw=true)

* The students who get chocolate with each trip are highlighted in the same color as Sr# column.
* Based on the above approach, total round trips that are required to complete the distribution on chocolates = 9.

~~~~~
Based on the number of round trips for each solution, Solution 1 is a more optimized approach.
~~~~~~~~~~~~~~~~~~~~~~~~~
