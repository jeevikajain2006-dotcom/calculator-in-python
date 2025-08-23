c="CALCULATOR"
print(c.center(50))
print("enter first number")
a=float(input())
print("enter second number")
b=float(input())
print("ener operator (+,-,*,/,%)")
op=input()
if op == "+":
    print("the sum of",a,"and ",b,"is",a+b)
elif op == "-":
    print("the difference of",a,"and",b,"is",a-b)
elif op == "*":
    print("the multiply of",a,"and",b,"is",a*b)
elif op == "/":
    print("the divide of",a,"and",b,"is",a/b)
elif op == "%":
    print("the remainder of",a,"and",b,"is",a%b)

