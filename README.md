
"""write a program that prints the numbers from 1 to 100. For multiples of three,print "fuzz" ;
For multiples of 5, print "buzz" ;and for numbers that are multiples of both 3 and 5
 print "fizzbuzz" """ 
 
for num in range(0,  100):
    num+=1
    if num %3==0 and num%5==0:
        print("fizzbuzz")
    elif num%5==0:
           print("buzz")
     elif num % 3==0:
           print("fizz")
    else:
               print( num)
