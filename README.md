# upgrad-assignment-
Python program to display all the prime numbers using for loop and range function

to find prime no :- 
given no are 1 and 200
a =1
b =200

print("Prime numbers are between", a, "to", b, "are:") 

for num in range(a , b + 1):
   # all prime numbers are greater than 1
  if num > 1:
        for i in range(2, num):
           if (num % i) == 0:
               break
       else:
            print(num)
        
 
