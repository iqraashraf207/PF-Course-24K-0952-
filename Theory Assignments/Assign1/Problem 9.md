**IPO Chart**

![9](https://github.com/user-attachments/assets/068b5a47-8f20-4d05-9985-e945c9d72512)

**Flowchart**
![9](https://github.com/user-attachments/assets/4579e00f-f019-4e19-829b-059bdeb5fb81)

**Pseudocode**
1.	Start
2.	Input bdm, bdd, bdy, tm, td, ty
3.	If month==1 || month==3 || month==5 || month==7 || month==8 || month==10 || month==12 && day>=1 && day<=31, then print date is valid
4.	Let age = ty-by
5.	If tm<bdm ||tm==bdm || td==bdd, then 
6.	Let age=age-1
7.	Print age is, age 
8.	Else print age is, age
9.	Else if month==4 || month==6 || month==9 || month==11 || month==8 || month==10 || month==12 && day>=1 && day<= 30, then print date is valid
10.	Let age = ty-by
11.	If tm<bdm ||tm==bdm || td==bdd, then 
12.	Let age=age-1
13.	Print age is, age 
14.	Else print age is, age
15.	Else if month==2 && day>=1 || day<=29, then check
16.	If day==29, then check
17.	If year%4==0, then print date is valid
18.	Else print date is invalid
19.	STOP
20.	Else print date is valid
21.	Let age = ty-by
22.	If tm<bdm ||tm==bdm || td==bdd, then 
23.	Let age=age-1
24.	Print age is, age 
25.	Else print age is, age
26.	End

In this problem, we need to calculate the  age. We will input the birth date, month and year and today date, month and year. We then need to verify if the input dates are valid or not. For this, we have set certain conditions which if true tell that input date is valid. To calculate age, we will minus today year and birthyear. If the birthday of this year has passed, then this will be the age otherwise minus 1 from the age.
