match-case statement:
----------------------
==> This statement is used to check multiple  options.
==> It is introduced in 3.10 version onwards.                  
==> It is similar to switch-case statement in
    c/c++/java/javascript.


===> syntax:

            match expression:  
                case value-1:
                    st-1
                case value-2:
                    st-2
                case value-3:
                    st-3
                case value-4:
                    st-4
                case value-n:
                    st-n
                ---
                ---
                case other:
                    default statements


ex-1: write a program to enter day number and print it words 
daynum= int(input('Enter day number'))

match daynum:
    case 0:
        print('SUNDAY')
    case 1:
        print('MONDAY')
    case 2:
        print('TUESDAY')
    case 3:
        print('WEDNESDAY')
    case 4:
        print('THURSDAY')
    case 5:
        print('FRIDAY')
    case 6:
        print('SATURDAY')
    case other:
        print('Invalid day number and please enter correct number.....')








ex-2: write a program to enter month number and print it words  
mnum = int(input('Enter month number'))

match mnum:      
    case 1:
        print('JANUARY')
    case 2:
        print('FEBRUARY')
    case 3:
        print('MARCH')
    case 4:
        print('APRIL')
    case 5:
        print('MAY')
    case 6:
        print('JUNE')
    case 7:
        print('JULY')
    case 8:
        print('AUGUST')
    case 9:
        print('SEPTEMBER')
    case 10:
        print('OCTOBER')
    case 11:
        print('NOVEMBER')
    case 12:
        print('DECEMBER')
    case other:
        print('Invalid month number and please enter correct number.....')



ex-3: write a program to enter any single digit number
      and print it words
method-1:  
num = int(input('Enter any single digit number(0-9)?'))
match num:
    case 0:
        print('ZERO')
    case 1:
        print('ONE')
    case 2:
        print('TWO')
    case 3:
        print('THREE')
    case 4:
        print('FOUR')
    case 5:
        print('FIVE')
    case 6:
        print('SIX')
    case 7:
        print('SEVEN')
    case 8:
        print('EIGHT')
    case 9:
        print('NINE')    
    case other:
        print('Invalid input.....')


method-2:  
num = int(input('Enter any single digit number(0-9)?'))
num = abs(num)
match num:
    case 0:
        print('ZERO')
    case 1:
        print('ONE')     
    case 2:
        print('TWO')
    case 3:
        print('THREE')
    case 4:
        print('FOUR')
    case 5:
        print('FIVE')
    case 6:
        print('SIX')
    case 7:
        print('SEVEN')
    case 8:
        print('EIGHT')
    case 9:
        print('NINE')    
    case other:
        print('Invalid input.....')


method-3:   
num = int(input('Enter any single digit number(0-9)?')) 
match num:
    case 0:
        print('ZERO')
    case 1 | -1:
        print('ONE')     
    case 2 | -2:
        print('TWO')
    case 3 | -3:
        print('THREE')
    case 4 | -4:
        print('FOUR')
    case 5 | -5:
        print('FIVE')
    case 6 | -6:
        print('SIX')
    case  7 | -7:
        print('SEVEN')
    case 8 | -8:
        print('EIGHT')
    case 9 | -9:
        print('NINE')    
    case other:
        print('Invalid input.....')


ex-4:  
x = 'abc'
match x:
    case 'INDIA':
        print('My current country INDIA')
    case 'CHINA':
        print('My current country CHINA')
    case 'USA':
        print('My current country USA')
    case other:
        print('country less...')
    
    


ex-5: write a program to enter two numbers
      and to perform arithmetic operations  
a = 9
b = 5
op = '*'

match op:
    case '+':
        c=a+b
        print(c)
    case '-':
        c=a-b
        print(c)
    case '*':
        c=a*b
        print(c)
    case '/':
        c=a/b
        print(c)
    case _:
        print('Invalid arithmetic operator  ..')



ex-6:  
x = False
x = True
x = 55

match x:
    case True:
        print('I am true block ...')
    case False:
        print('I am false block ...')
    case other:
        print('Different input ....')
