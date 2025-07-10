simple programs

----------------------------
     

1. write a program to display Hello world message  


print('Hello world')



2. write a program to display Good Morning To All message  


print('Good Morning To All')



3. write a program to find addition of two numbers  
method-1: static initialization   
a = 4
b = 5
c = a+b
print(c)


method-2: dynamic initialization   
a = input('Enter first value')
b = input('Enter second value')
c = a+b
print(c)


method-3: dynamic initialization  
a = int(input('Enter first value'))
b = int(input('Enter second value'))
c = a+b
print('Addition value  =  ', c)


 

4. write a program to find area of a rectangle.
                 Hint : area  = length * bredth    
 
l = int(input('Enter length value'))
b = int(input('Enter breadth value'))
area = l*b
print('Area of a rectangle  =  ', area)


5. write a program to find area of a circle.

                 Hint : area  = pi r   
method-1:  '
r = int(input('Enter radius value'))
 
area =  3.14*r*r
print('Area of a circle  =  ', area)


method-2:  
import math
r = int(input('Enter radius value'))
 
area =  math.pi*r**2
print('Area of a circle  =  ', area)


6. write a  program to get student information,
        i.e. htno,name of the student and three subject marks.
        To find total and average.   

htno =  int(input('Enter Hall ticket Number'))
studname = input('Enter student Name  :')
m1 =  int(input('Enter first subject Marks'))
m2 =  int(input('Enter second subject Marks'))
m3 =  int(input('Enter third subject Marks'))


total = m1+m2+m3
avg = total/3

print('\t\t\t\t******')
print('\t\t\t\tSTUDENT RESULT')
print('\t\t\t\t******')
print('\t\t\tTotal Marks  =  ',total)
print('\t\t\tAverage Marks  =  ',avg)


6. write a  program to get employee information, and print it ?    

empid =  int(input('Enter Employee Number'))
empname = input('Enter Employee Name  :')
empsal =  float(input('Enter Employee salary'))



print('\t\t\t\t********')
print('\t\t\t\tEMPLOYEE INFORMATION')
print('\t\t\t\t********')
print('\t\t\tEmployee Number  =  ',empid)
print('\t\t\tEmployee Name  =  ',empname)
print('\t\t\tEmployee salary  =  ',empsal)

chr():

===> It returns character of the given ASCII value.
ex:
chr(97)
'a'
chr(122)
'z'
chr(67)
'C'
chr(90)
'Z'
chr(65)
'A'
chr(66)
'B'


 
 
ord()
===> It returns ASCII value of the given character.

ord('d')
100
ord('A')
65
ord('a')
97
ord('D')
68



abs():
-------
==> abs stands absoulute
==> if the given number is negative number,
    to convert negative number into    positive number.
  ex:

abs(-9)
9
abs(25)
25
abs(-25)
25
abs(-3)
3


Assignment - 1
-------------------------------
                    Simple Programs
1. Write a program in Python to print 'Hello World'
2. write a program to demonstrate arithmetic operators
3. write a program to demonstrate relational operators4.  Write a Python program which accepts the user's first and
    last name and print them in reverse order with a space between them.

5. write a  program to find  addition of two numbers
6. Write a Python program to find  the volume of a sphere .
7. write a program to find the area of a circle
8. Write a Python program to find the area of a rectangle
9. write program to find the roots of  the quadratic equation 
            ax**2 + bx + c = 0
10. Write a program to convert kilometers to miles
11. Write a Program to convert temprature in celsius to fahrenheit
12. Write a Python program that accepts an integer (n) and
    computes the value of n+nn+nnn.
        
13. Python Program to Calculate Simple Interest
14. Write a Python program to calculate Body Mass Index(BMI).
15. Write a Python program to swap two variables in single line 
16. Write a program in Python to print 'Hello World' 30 times on the screen.
17. Write a program in Python to find total and average 
18. Python Program to find the Last Digit in a Number
19. Python Program to Find the Square Root of given number20.  write a program to convert the decimal number  into binary,octal, hexadecimal numbers
21. Write a program to demonstrate all data types:22.  Write a python program to add  two binary number
23. Write a program to print ASCII value of a given character.
24. Write a program to print character of a given integer
25. Python Program to find Sum of Arithmetic Progression Series
26. Python Program to find Sum of Geometric Progression Series
27. Python Program to find Volume and Surface Area of Sphere
28. Python Program to find Volume & Surface Area of a Cylinder
29. Python Program to find Volume and Surface Area of a Cube
30. Python Program to find Compound Interest  .
31. write a python program to find your age?
