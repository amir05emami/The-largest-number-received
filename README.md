# The-largest-number-received
a = float(input('num1: '))
b = float(input('num2: '))
c = float(input('num3: '))
if a>c>b or a>b>c:
    print(a)
elif b>a>c or b>c>a:
    print(b)
elif c>a>b or c>b>a:
    print(c)
