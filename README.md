# Multiples-of-3-and-5 
#Answer 

c = 1000 # The set number
d = 3 # A multiple number 1
e = 5 # A multiple number 2


a = 0 # To go though all of the positive whole the numbers below the value of c
sum = 0 # The sum of all the multiples within c


while a %d or e !=0:
    a += 1 # Goes though all the positive whole numbers
    if a %d ==0:
        sum += a # Stops at a multiple of d and adds it to the sum and then continues
    if a %e ==0 and a %d !=0: #stops duplicates
        sum += a # Stops at a multiple of e and adds it to the sum and then continues
    if a == c - 1:
        print(sum) # Prints the sum at one less of the set number
        break
