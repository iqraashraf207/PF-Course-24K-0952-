**IPO Chart**

![10](https://github.com/user-attachments/assets/8dd70642-af2a-4c94-bdfb-df7166312a6e)

**Flowchart**
![10](https://github.com/user-attachments/assets/101209d9-46d6-4385-8984-3130f2676797)

**Pseudocode**
1.	Start
2.	Input num
3.	While (num! = 0) do
4.	digit1=num%10
5.	If digit1! = 0, print digit1
6.	Else num=num//10
7.	digit2=num%10
8.	If digit2==9, print digit9
9.	Else print digit1
10.	num=num//1
11.	Endwhile
12.	Let revnum=0
13.	While (num>0) do
14.	digit3=num%10
15.	revnum =revnum*10+digit3
16.	num =num//10
17.	Endwhile
18.	Print revnum
19.	End 


The problem requires designing a solution for Mr. Bhoola that will help fix the inputs of his faulty keyboard.Whenever he types 9 it also adds an additional 0 along with it. To fix this problem, we will find digit=number % 10 which if not equal to 0 will be written same. If equal to zero, then we will do number // 10 and if that equals 9, then we will print 9 otherwise we will print the 0. This will be repeated until number equals zero. This fixes the issue of the faulty keyboard but the number is printed in reverse now. We will write it in original by taking number % 10. Then we will do revnumber=revnumber * 10 +digit (initially revnumber=0). Afterwards take number// 10. This process will continue until number equals 0. Our problem is now fixed completely. 
