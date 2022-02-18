# ass-1-18-02-22
program to print count of n prime numbers
 numr=int(input("Enter range:"))

print("Prime numbers:",end=' ')

for n in range(1,numr):

    for i in range(2,n):

        if(n%i==0):

            break

    else:

        print(n,end=' ')
 output:
 Enter range: 50
Prime numbers: 1 2 3 5 7 11 13 17 19 23 29 31 37 41 43 47
