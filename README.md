# MV1
this calculates your maturity value
# File: MV1.py


p = int(input("enter monthly installments:"))
t = int(input("enter time period:"))
r = int(input("enter rate of intrest:"))

n = t*12
A = p*n
B = n+1
C = A*B*r
I = C/2400
MV = A+I
print("maturity value:")
print(MV)

input()
