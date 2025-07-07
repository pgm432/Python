operators in python
                    ------------------------

what is operator?
==> A opertor is a mathematical symbol
   It is used either calculation  / comparison between two values.

 
         ex-1: calculation purpose
                     a + b
                     + operator
                here,
                  a ,b are called variables / operands / objects

        ex-2: comparison purpose
                     a < b
                here,
                  a ,b are called variables / operands / objects.
                 <   lessthan operator


===> python supports 6 types of operators. These are


                    1. Arithmetic operators
                    2. Relational operators
                    3. Logical operators
                    4. bitwise operators
                    5. Assignment operators
                    6. special operators
                        a). identity operators
                        b). membership operators





1. Arithmetic operators:
--------------------------
==> these operators are used for calculation purpose.
==> It returns value.


                       operator   meaning
                         +      addition operator
                         -      subtraction operator
                         *      mulplication operator
                         /      division operator
                         //     floor division
                         %      remainder (or) modulo operator
                         **     exponent operator (or) power operator

ex-1: write a program demo for arithmetic oeprators  ' 
a = 9
b = 2
print(a+b)
print(a-b)
print(a*b)
print(a/b)
print(a**b)
print(a//b)
print(a%b)


ex-2: write a program demo for arithmetic operators
x = 10
y = 3
print(x+y)
print(x-y)
print(x*y)
print(x/y)
print(x//y)
print(x**y)
print(x%y) 

ex-3:  write a program concatenation of two strings
s1 = 'hello'
s2 = 'good'
print(s1+s2)    
 
ex-4:   write a program concatenation of two strings
s1 = 'hello'
s2 = 'good'
s3 = s1+s2
print(s3)    
  

ex-5:   write a program repeat a given string
s1 = 'hello'
s2 = 'good' 
print(s1*5)    
print(s2*10)

 

 
 Note-1:
     In case of strings:

       ====>   + operator is called concatenation operator
               It is used concatenation of two or more strings.
               The result is stored into another string.


  Note-1:
     In case of strings:

       ====>   * operator is called repetition  operator
               It is used to repeat a string 'n' NO. of times.
 
2. Relational operators:
--------------------------
==> These operators are used for comparison purpose.
==> It returns either True / False


                       operator   meaning
                          <     lessthan operator
                          >     greater than  operator
                          <=    lessthan or equal to operator
                          >=    greater than or equal to operator
                          ==    equal to operator
                          !=    not equal to operator

ex-1:  
a = 9
b = 2
print(a<b)
print(a>b)
print(a<=b)
print(a>=b)
print(a==b)     
print(a!=b)



ex-2:  
x = 10
y = 35
print(x<y)   
print(x>y)    
print(x<=y)  
print(x>=y)  
print(x==y)   
print(x!=y)   


ex-3:  
s1 = 'hello'
s2 = 'good'
print(s1<s2)    
print(s1>s2)   
print(s1<=s2)
print(s1>=s2)
print(s1==s2)
print(s1!=s2)
 

 

3. Logical opeartors:
---------------------------
===> These operators are used connect two or more relational expressions.

                    operator   meaning
                      and     logical and operator
                      or      logical or operator
                      not     logical not operator


logical and operator:
------------------------
===> If both relational expressions returns True, then,
     result is True.
==> otherwise , the result is False
==> Truth table:

                  RE-1    RE-2     RESULT
                    T       T        T
                    T       F        F
                    F       T        F
                    F       F        F

True and True
True
True and  False
False
False and  True
False
False and False
False
 


logical or operator:
------------------------
===> If any one relational expressions returns True, then,
     result is True.
===> otherwise , the result is False

==> Truth table:

                  RE-1    RE-2     RESULT
                    T       T        T
                    T       F        T
                    F       T        T
                    F       F        F
 

True or True
True
True or False
True
False or True
True
False or False
False



logical not operator:
------------------------
===> If   relational expressions returns True, then, result is False
===> If   relational expressions returns False, then,  result is False

==> Truth table:

                  RE-1        RESULT
                    T           F
                    F           T
                  
not True
False
not False
True
