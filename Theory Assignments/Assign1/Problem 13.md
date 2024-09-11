**IPO Chart**

![13](https://github.com/user-attachments/assets/041fa1bb-9e74-4624-853e-5ecbd85811ac)

**Flowchart**

![13](https://github.com/user-attachments/assets/18a6a94a-9527-4916-a1dc-4dfa0c0f2736)

**Pseudocode**
1.	Start
2.	Input m, n
3.	Let jugm=m
4.	Jugn=n
5.	Jugn=jugn-jugm
6.	Let Jugm=0
7.	Jugm=jugn
8.	Let jugn=0
9.	Jugn=n
10.	Let space=m-jugm
11.	Jugn=jugn-space
12.	Jugm=jugm + space
13.	Print the liters are, jugn
14.	End 

This problem requires designing a solution to check if we can extract any number of liters less than the larger jug. To do this we will fill the larger jug with water and transfer it to the smaller one. This leaves us with water in the larger jug minus the liters of the smaller one. We will empty the smaller jug and transfer the remaining liters of the larger jug to the smaller one. Again fill the larger jug and pour water to the smaller jug already filled with the previous liters of the larger jug. Now the larger jug is filled with some quantities less than its original capacity.
