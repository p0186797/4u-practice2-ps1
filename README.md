# 4u-practice2-ps1

Create a java file called **Practice2.java** and upload it to this repo. For each program, do not have any extraneous print statements i.e. no prompts. The output must be exact.

---

Inside that file create a class called **TotalQuestion**.

Write a program that reads 1 line of input from the user consisting of numbers separated by a space. For example: 231 232 23 565.

Your program outputs the total.

&nbsp;&nbsp; **Sample Input 1**

    1 1 1 1 1 1 1 1 1 1

&nbsp;&nbsp; **Sample Output 1**

    10

&nbsp;&nbsp; **Sample Input 2**

    10 100 21 1

&nbsp;&nbsp; **Sample Output 2**

    131

---

Inside that file create a class called **BaseQuestion**.

Write a program that reads 1 line of input from the user consisting of a sequence of digits. For example: 123456.

Your program outputs the largest possible base the number can be in. 

A base n number uses n digits: 0 to n - 1 where n is 10 or less.

&nbsp;&nbsp; **Sample Input 1**

    123456

&nbsp;&nbsp; **Sample Output 1**

    7

&nbsp;&nbsp; **Sample Input 2**

    5000000

&nbsp;&nbsp; **Sample Output 2**

    6
    
---

Inside that file create a class called **SudokuQuestion**.

Write a program that reads one line from the user containing 9 single digits made of digits 1, 2, 3 separated by a space. 

For example: 1 2 3 3 1 2 2 3 1

This line of input represents a 3 x 3 sudoku board.

For example:

1 2 3
3 1 2
2 3 1

Your program should output if the sudoku board has the correct format i.e. it has 9 single digits separated by a space and has exactly 2 occurences of 1 ,2 and 3 each.

&nbsp;&nbsp; **Sample Input 1**

    1 2 3 3 3 3 2 1

&nbsp;&nbsp; **Sample Output 1**

    no
    
&nbsp;&nbsp; **Sample Input 1**

    1 2 3 3 1 2 2 3 1

&nbsp;&nbsp; **Sample Output 1**

    yes
    
---

Inside that file create a class called **AddressQuestion**.

Write a program that reads one line from the user and outputs if the line represents a valid IP address.

An IP address contains 4 numbers separated by a period. Each number must be between 0 and 255 inclusive. Aside from the number 0, the numbers should not contain leading 0's.

&nbsp;&nbsp; **Sample Input 1**

    0.255.0.255

&nbsp;&nbsp; **Sample Output 1**

    yes

&nbsp;&nbsp; **Sample Input 2**
    
    123.4.32.200

&nbsp;&nbsp; **Sample Output 2**

    yes

&nbsp;&nbsp; **Sample Input 3**

    00.00.00.00

&nbsp;&nbsp; **Sample Output 3**

    no
    
---
