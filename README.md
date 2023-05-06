# Python_assignment--1
num = int(input())                        # number: 9
num1 = 0
num2 = 1
if num < 1:
    print(num1,end=" ")
elif num >= 1:
    print(num2,end=" ")
    for x in range(1,num):
        num3 = num1 + num2
        num1 = num2
        num2 = num3
        print(num3,end=" ")                # output: 1,1,2,3,5,8,13,21,34
