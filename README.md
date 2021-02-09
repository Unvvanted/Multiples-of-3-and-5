# Multiples-of-3-and-5 
#Question By Project Euler
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
Find the sum of all the multiples of 3 or 5 below 1000.

#Answer: By me 233168


a = 0
c = 1000
b = 0 

d = 3 
e = 5 

while a %d or e !=0:
    a += 1 
    if a %d ==0:
        b += a 
    if a %e ==0 and a %d !=0: 
        b += a 
    if a == c - 1:
        print(b) 
        break
