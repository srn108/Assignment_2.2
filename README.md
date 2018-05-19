# Assignment_2.2
# Program to print a pattern using for nested loop

n = 5

for i in (range(n)):
    for a in range(i):
        print("*", end =" ")
    print("")

for i in range(n,0,-1):
    for a in range(i):
        print("*", end=" ")
    print("") 
