# Multiples-of-3-and-5 
#Question By Project Euler
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
Find the sum of all the multiples of 3 or 5 below 1000.

Answer: By me

c = 1000
d = 3 
e = 5 
a = 0
sum = 0 

while a %d or e !=0:
    a += 1 
    if a %d ==0:
        sum += a 
    if a %e ==0 and a %d !=0: 
        sum += a 
    if a == c - 1:
        print(sum) 
        break
