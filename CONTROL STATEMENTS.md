CONTROL STATEMENTS
                       (OR)
                     control structures
                       (or)
                     FLOW CONTROL
                    ---------------------

==> python supports 3 types of control statements. These are:
             1. conditional control statements
             2. Iterative control statements
             3. Transfer control statements


  

                         FLOW CONTROL
                            |
                            |
                            |
                            |
    ------------------------------------------------------ 
    |                          |                        |
    |                          |                        |
    |                          |                        |
    |                          |                        |
  conditional               Iterative               Transfer
  control statements        control statements      control statements
   |                             |                    |
   |---> if                      |--> while           |---> break
   |---> if-else                 |--> for             |---> continue
   |---> if-elif                                      |---> pass
   |---> if-elif-else
   |---> single line if           
   |---> nested if
   |---> match-case
   |
   
     


conditional control statements :
----------------------------------
===> These statements are executed based on condition.

   ex-1: 




                        booking
                        counter
                          |
                          |
                          |
                True      |    False
              -------------------------
              |                       |
              |                       |
              |                       |
              |                       |
            cinema                  goto hotel
              |                       |
              |                       |
              |                       |
              |--------home-----------|



      ex-2: 

                         B.Tech
                          |
                          |
                          |
                True      |    False
              -------------------------
              |                       |
              |                       |
              |                       |
              |                       |
            Learning courses       TO WRITE SUPPLY EXAMS
              |                       |
              |                       |
              |                       |
              |--------JOB------------|


                               
                1. if statement                      
                2. if-else  statement                
                3. if-elif statement                                      
                4. if-elif-else statement
                5. single line if statement
                6.  nested if statement
                7.  match-case statement





1. if statement : 
------------------------

syntax:
                 if condition:
                     st-1
                   


          Here,
             ====>  if is a keyword.
             ====>  condition returns either True / False.
             ====>  if the given condition returns True, then,
                    st-1 is exeucted  
             ====>   if the given condition returns False, then,
                    st-1 is not exeucted .
                    
ex-1:   
if True:
    print('I am true block')
 


ex-2:   
if False:
    print('I am true block')
 


   
2. if-else  statement:
---------------------- 
===>

                 syntax:
                         if condition:
                               st-1
                         else:
                               st-2
                               


            Here,
            ==> if,else are keywords.
            ==> if the given condition returns True, then,
                st-1 is executed and st-2 is not executed.
            ==> if the given condition returns False, then,
                st-1 is not executed and st-2 is  executed.
            
ex-1:  
if True:
      print('I am True block. ....')
else:
      print('I am False block. ....')
                     

ex-2:  
if False:
      print('I am True block. ....')
else:
      print('I am False block. ....')
                      
ex-3: write a program to find the biggest of two numbers  


a = int(input('Enter first number'))
b = int(input('Enter second number'))

if a>b:     
      print('A is biggest')
else:
      print('B is biggest')


ex-4: write a program to find   

marks = 5

if marks>=35:
      print('pass')
else:
      print('fail')


ex-5: write a program     

bal = 9500
withdraw_amount = int(input('Enter withdraw amount'))

if withdraw_amount<=bal:
      print('collect cash ...')
      bal = bal - withdraw_amount
      print('After withdraw , your current balance = ' ,bal)
else:
      print('Insufficient Funds ....')


ex-6: write a program to check you are eligible for voting or not ?  

age = int(input('Enter your age'))

if age>=18:
      print('congrats  ...')
      print('you are Eligible for voting')
      print('please participate present elections .....')
else:
      print('sorry  ...')
      print('you are Not Eligible for voting')
      print('please apply next elections ...')
      
 

ex-7: write a program to check , the given number is even or  odd ?  

n = int(input('Enter any number'))

if n%2==0:
      print('Even  Number')
      
else:
      print('Odd Number') 

 
  
3. if-elif statement:
---------------------

===> This statement is used to check multiple conditions.
===> Syntax:

                    if condition-1:    
                        st-1
                    elif condition-2:
                        st-2
                    elif condition-3:
                        st-3
                    elif condition-4:
                        st-4
                    --
                    --
                    elif condition-n:
                        st-n
                        
                    
       Here,
     ===>  if,elif are keywords
     ===>  if the condition-1 returns True, then,st-1 is executed.
     ===>  if the condition-1 returns False, then,st-1 is not executed.
           and to check condition-2.


     ===>  if the condition-2 returns True, then,st-2 is executed.
     ===>  if the condition-2 returns False, then,st-2 is not executed.
           and to check condition-3.

     ===>  if the condition-3 returns True, then,st-3 is executed.
     ===>  if the condition-3 returns False, then,st-3 is not executed.
           and to check condition-4.


    -----and so on
     ===>  if the condition-n returns True, then,st-n is executed.
     ===>  if the condition-n returns False, then,st-n is not executed.
           and  do nothing.



ex-1:  write a program to find the given number
        is positive number / negative number / zero number 

n = int(input('Enter any number'))

if n>0:
    print('Given Number is positive number')   
elif n<0: 
    print('Given Number is negative number')
elif n==0:
    print('Given Number is zero number') 

       

ex-2: write a program to find biggest of two numbers    

a = int(input('Enter first value'))
b = int(input('Enter second value'))

if a>b:
    print('A is biggest')
elif b>a:
    print('B is biggest')
elif a==b:
    print('A & B are Equal')







 
4. if-elif-else statement:
---------------------

===> This statement is used to check multiple conditions.
===> Syntax:

                    if condition-1:    
                        st-1
                    elif condition-2:
                        st-2
                    elif condition-3:
                        st-3
                    elif condition-4:
                        st-4
                    --
                    --
                    elif condition-n:
                        st-n
                    else:
                        else block
                        


   Here,
     ===>  if,elif,else are keywords
     ===>  if the condition-1 returns True, then,st-1 is executed.
     ===>  if the condition-1 returns False, then,st-1 is not executed.
           and to check condition-2.


     ===>  if the condition-2 returns True, then,st-2 is executed.
     ===>  if the condition-2 returns False, then,st-2 is not executed.
           and to check condition-3.

     ===>  if the condition-3 returns True, then,st-3 is executed.
     ===>  if the condition-3 returns False, then,st-3 is not executed.
           and to check condition-4.


    -----and so on
     ===>  if the condition-n returns True, then,st-n is executed.
     ===>  if the condition-n returns False, then,st-n is not executed.
           and else block will be executed.
             

ex-1: write a program To enter day number and print it words   
                0 ====> SUNDAY
                1 ====> MONDAY
                2 ====> TUESDAY
                --
                --
                6 ====> SATURDAY    '''

daynum = int(input('Enter day number(0-6)?'))
if daynum==0:
    print('SUNDAY')
elif daynum== 1:
    print('MONDAY')
elif daynum==2 :
    print('TUESDAY')
elif daynum==3 :
    print('WEDNESDAY')
elif daynum==4:
    print('THURSDAY')
elif daynum==5 :
    print('FRIDAY')
elif daynum== 6:
    print('SATURDAY')
else:
    print('Invalid input,...pls enter correct inpput...')


 
'''


ex-2: write a program to enter month number and print it words   
                 
                1 ====> JANUARY
                2 ====> FEBRUARY
                --
                --
                12 ====> DECEMBER  

monnum = int(input('Enter month number(1-12)?'))
if monnum== 1:
    print('')
elif monnum==2 :
    print('')
elif monnum==3 :
    print('')
elif monnum==4:
    print('')
elif monnum==5 :
    print('')
elif monnum== 6:
    print('')
elif monnum==7 :
    print('')
elif monnum==8 :
    print('')
elif monnum==9:
    print('')
elif monnum==10 :
    print('')
elif monnum== 11:
    print('')
elif monnum== 12:
    print('')    
else:
    print('Invalid input,...pls enter correct inpput...')



ex-3: write a program to enter any single digit number and print it words    
                0  ==> ZERO  
                1 ====> ONR
                2 ====> TWO
                --
                --
                9 ====> NINE  
  
ex-4: write a program enter any two numbers and arithmetic operator.
     To perform arithmetic operation  

                1===> Addition
                2===> subtraction
                3===> multiplication
                4===> division

 [7:56 AM, 7/12/2025] Kusu Srinivasa Rao Python: single line if  statement:
--------------------------
===> A if statement written in only one line.
     It is called single line if statement.

===> syntax:
                  st-1 if condition  else st-2
 


ex-1: 

print('I am True block') if True  else print('I am False block')


ex-2:  

print('I am True block') if False  else print('I am False block')



ex-3:  
n = -3

print('Positive Number') if n>0  else print('Negative Number')
                          

ex-4: write a program to find given number is even number or odd number 

n = int(input('Enter any number'))

print('Even') if n%2==0  else print('Odd')



ex-5: write a program to find biggest of two numbers  

n1 = int(input('Enter first number'))
n2 = int(input('Enter second number'))

print('First number is biggest number') if n1>n2  else print('Second number is biggest number')
[7:56 AM, 7/12/2025] Kusu Srinivasa Rao Python: nested if statement
---------------------
===> A if statement inside another if statement.
     It is called nested if statement.
             
syntax-1:

                    if condition-1:
                        if condition-2:
                            st-1       
                        

syntax-2: 

                    if condition-1:
                        if condition-2:
                            st-1        
                        else:
                            st-2
                    else:
                        st-3


syntax-3:
                    if condition:
                        if condition:
                            st        
                        elif condition:
                            st
                        elif condition:
                            st
                        elif condition:
                            st
                        --
                        --
                        elif condition:
                            st
                        else:
                            st                            
                    else:
                        st





write a program to find you are eligible for blood donation or not?
         requirements:
                     age>=21
                     weight>=45       

age = int(input('Enter your age'))

if age>=21:  
    weight = int(input('Enter your weight'))    
    if weight>=45:      
        print('you are eligible for blood donation')        
    else:
        print('Not eligible for blood donation')
        print('Because')
        print('You are Under Weight')
else:
    print('Not eligible for blood donation')
    print('Because')
    print('You are Under Age')

 


write a program to read student information hall ticket number,
name of the student and three subject marks.
To find total,average , result and grade  '''

htno = int(input('enter student Hall ticket number'))
studname = input('enter student name')
m1 = int(input('enter first subject marks'))
m2 = int(input('enter second subject marks'))
m3 = int(input('enter third subject marks'))

total = m1+m2+m3
avg = total/3 
 
if m1>=35 and m2>=35 and m3>=35:
    result = 'PASS'
    if avg>=70:
        grade='A+ Grade'        
    elif avg>=60 and avg<70:
        grade='A Grade'
    elif avg>=50 and avg<60:
        grade='B Grade'
    elif avg>=35 and avg<50:
        grade='C Grade'   
else:
    result = 'FAIL'
    grade = 'F - Grade'

 
print(total)
print(avg)
print(result)
print(grade)



