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

4. bitwise operators
                    5. Assignment operators
                    6. special operators
                        a). identity operators
                        b). membership operators




 
 
 
 
 
   

 
4. bitwise operators:
------------------------
====> These operators are used to perform operations at bit level.
    
====> bit stands binary digit.
====> It represents either 0,1.

 
                  operators   meaning
                    &    bitwise and operator
                    |    bitwise or operator
                    ^    bitwise exclusive or operator
                    ~    bitwise complement operator
                    <<   bitwise rightshift operator
                    >>   bitwise rightshift operator
 


5. Assignment operators:
-------------------------
===> These operators are used to store the value into a variable.

    ex-1:
              x =  8



    ex-2:   s = 'tronix technologies'
    

 



        operator     meaning                          example
          =      simple Assignment operator           x = 9
          +=     Addition Assignment operator         x=x+6 (or)  x+=6
          -=     subtraction Assignment operator      x=x-8 (or)  x-=8
          =     multiplication Assignment operator   x=x*25 (or) x=25
          /=     division Assignment operator         x=x/6  (or)  x/=6
          //=    floor division Assignment operator   x=x//5 (or) x//=5
          %=     modulo Assignment operator           x=x%10 (or) x%=10
          *=    exponent Assignment operator         x=x6 (or) x*=6
          

ex-1: write a program demo for assignment operators  
m = 9
print(m)
m+=3
print(m)
m-=6
print(m)
m*=4
print(m)
m//=10
print(m)
m**=6
print(m)
m/=3
print(m)
m%=8
print(m)


 
ex-2: write a program demo for assignment operators  

k = 10
print(k)
k+=4
print(k)
k*=9
print(k)
k-=4
print(k)
k//=8
print(k)
k%=2
print(k)
k**=4
print(k)
k/=3
print(k)


 

  Memory requirement :                      


In java:

     x = 6
     y = 3
     z = 6
     a = 3
     b = 35
     c = 6
     d = 2









     In java, Total Memory requirement  ===> 7x4 bytes
                                        ===> 28 bytes
                                        
In python:

     x = 6
     y = 3
     z = 6
     a = 3
     b = 3 
     c = 6
     d = 2

     In python, Total Memory requirement  ===> 3x4 bytes
                                          ===> 12 bytes
                                    

type():
    It returns data type of the given variable

ex-1:  
x = 9
print(x)
print(type(x))

ex-2:  
x = 9.6
print(x)
print(type(x))


ex-3: 
x = '9'
print(x)
print(type(x))


ex-4:  
x = 9+8j
print(x)
print(type(x))

ex-5:  
x = True
print(x)
print(type(x))


#id():
==> It returns address of the given variable
ex-1:     
x = 9
print(x)
print(type(x))
print(id(x))

ex-2:  
x = 9.6
print(x)
print(type(x))
print(id(x))


ex-3: 
x = '9'
print(x)
print(type(x))
print(id(x))


ex-4:  
x = 9+8j
print(x)
print(type(x))
print(id(x))

ex-5:   
x = True
print(x)
print(type(x))
print(id(x))
 
 
6. special operators in python:
------------------------------
            a). identity operators
            b). membership operator
            
 
a). identity operators:
---------------------- 
===> these operators are used to find both objects are same location
    or different locations.
==>  identity operators are 2
                     is
                     is not

            is  ====> it returns eithe True / False.
                  if both variables are pointing same location,
                  then, it returns True. otherwise it returns False.

            
            is not ====> it returns eithe True / False.
                  if both variables are pointing different locations,
                  then, it returns True. otherwise it returns False.


ex-1:  
x = 9
y = 6
z = 9

print(x is y)
print(x is z)


b). membership operator
---------------------- 
===> these operators are used to find, the given value is present or not

==>  membership operators are 2
                     in
                     not in

            in  ====> it returns eithe True / False.
                  if given value is present,   
                  then, it returns True. otherwise it returns False.

            
            is not ====> it returns eithe True / False.
                  if given value is not present, 
                  then, it returns True. otherwise it returns False.


ex-1:   
s = 'tronix'

print('r' in s)
print('k' in s)
print('z' in s)

ex-2:  
s = 'python is a high level programming Language'
print('i' in s)
print('level' in s)
print('java' in s)
print('angu' in s)
print('animal' not in s)


ex-3:  
x = [11,22,33,44,55,66]
print(44 in x)
print(99 in x)
print(88 not in x)
print(22 not in x)
