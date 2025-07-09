input  ====> process   ====> output


  Aim                 input               process            output
1. To prepare         tea powder
   Tea                milk
                      water               boiling            tea
                      sugar

2. To prepare         mangoes
   Mango juice        ice                 mixing             mango juice
                      water

3. Addition of        a=11
   two numbers        b=22               c=a+b              print(c)

4. Area of a        length=8
   rectangle        breadth=9        area=length*breadth     print(area)







output statement in python:
-------------------------------
print():
----------
===> It is a built-in function (or) output statement.
===> This statement is used to display messages (or) variable values on the screen.

===> syntax:

          print(*args,sep,end,file,flush)


      Here,
         =====>  print() is a built-in function
         =====>  sep represents separator
         =====>  end represents end of the statement.
         =====>  file and flush are used in file handling
 

ex-1: To display message   
print('welcome to tronix technologies')


ex-2: To display message   
print('Good Morning to all')

ex-3: To display messages   
print('Good Morning to all')
print('welcome to tronix technologies')
print('welcome to tronix technologies')
print('welcome to python course')
print('welcome to sql')
print('welcome to html course')


ex-4: To display variable value  
a = 11
print(a)

ex-5:  To display variable values
a = 11
b = 22
c = 99
print(a)
print(b)
print(c)
print(a,b,c)


ex-6:  To display variable values 
a = 11
b = 22
c = 99
print('A value  =  ', a)
print('B value  =  ', b)
print('C value  =  ', c) 


EX-7: To display employee information  
empid = 1901
empname = 'ram kumar'
empsal = 96000.75

print('Employee Number  =  ', empid)
print('Employee Name  =  ', empname)
print('Employee salary  =  ', empsal)



EX-8: To display student information   
htno = 1901
studname = 'venkat'
m1=77
m2=88
m3=99

print('Student Hall ticket Number  =  ', htno)
print('student  Name  =  ', studname)
print('First subject marks   =  ', m1)
print('second subject marks   =  ', m2)
print('Third subject marks   =  ', m3)



ex-9: To display variable values  
day = 9
month = 7
year = 2025

print(day,month,year)


Note:

   By default separator is blank space.


ex-9: using separator parameter, To display date   
day = 9
month = 7
year = 2025

print(day,month,year)
print(day,month,year,sep='/')
print(day,month,year,sep='-')


ex-10: using separator parameter, To display time  
h = 7
m = 32
s = 51

print(h,m,s)
print(h,m,s,sep=':') 


ex-11: using separator parameter, To display  values  
s1 = 'Tronix'
s2 = 'Hyderabad'
print(s1,s2)
print(s1,s2,sep='')
print(s1,s2,sep=' ')
print(s1,s2,sep='+')
print(s1,s2,sep='-')
print(s1,s2,sep='*')
print(s1,s2,sep='&')
print(s1,s2,sep='^')
print(s1,s2,sep='%')
print(s1,s2,sep='$')
print(s1,s2,sep='#')
print(s1,s2,sep='@')
print(s1,s2,sep='!')
print(s1,s2,sep='~')
print(s1,s2,sep=';')
print(s1,s2,sep=':')


ex-12: using end parameter  

s1 = 'Tronix'
s2 = 'Hyderabad'
print(s1,end='')
print(s2)

 
ex-12: using end parameter   

s1 = 'Tronix'
s2 = 'Hyderabad'
print(s1,end=' ')
print(s2)


ex-13: using end parameter , with  \t 

s1 = 'Tronix'
s2 = 'Hyderabad'
print(s1,end='\t\t\t\t\t')
print(s2)

 
          Note:
            \t reprsents tab spaces
            i.e.  4 blank spaces (or) 4 white spaces

 
ex-14: using end parameter , with  \n  

s1 = 'Tronix'
s2 = 'Hyderabad'
print(s1,end='\n\n\n\n\n')
print(s2)



 
       Note:

            \n  ===> new line (or) next line

 

input():
------------
==> It is a built-in function.
==> This function is used,
    To get user input. (or) To read user input.
  ==> By default, the input function,
      to read string data type.

===> syntax:
  
             variablename = input('any prompt  ...')



ex-1:  
x = int(input('Enter pin number'))

ex-2:  
a = int(input('Enter your age'))


ex-3:   
sal = float(input('Enter your salary'))

'''

     static initialization
              To assign value before running. It is called static initialization
             

               x = 45



     Dynamic initialization:
                 To assign value at runtime. It is called Dynamic initialization
             



               x = int(input('Enter any number'))
