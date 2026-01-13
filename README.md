# python-program-27
coding
number=int(input("Enter any number:"))
if number>1:
    for i in range(2,number):
        if(number%i)==0:
            print(number,"s not a prime number")
            break
        else:
           print(number,"is a prime number")
else:
 print(number,"is not a prime number")
output
Enter any number:3
3 is a prime number
Enter any number:4
4 s not a prime number
