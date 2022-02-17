PROGRAMME:
n = int(input())

a = 0
b = 1
Sum = 0

for Num in range(0, n):
    print(a)
    Sum = Sum +a
    c = a + b
    a=b
    b=c

print("The Sum of Fibonacci Series Numbers = " ,Sum)

OUTPUT:
5
0
1
1
2
3
The Sum of Fibonacci Series Numbers =  7


