#Number1=0
#Number2=1 for starting fibonacci series from the beginning
Number1=int(input("please enter the first number:"))
Number2=int(input("please enter the second number:"))
LastNumber=int(input("Number of fibonacci series to be print:"))
print(Number1,end=" ")
print(Number2,end=" ")
for i in range(LastNumber+1):
    sum=Number1+Number2
    Number1=Number2
    Number2=sum
    print (sum,end=" ")
