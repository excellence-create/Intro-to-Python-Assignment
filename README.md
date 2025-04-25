# Intro-to-Python-Assignment
#calculator.py
A = float(10)
B = int(5.7)
C = float(20)
D = int(8.9)

#perform operation
if A + B == 15:
    result = A + B
    print("A + B =", result)
else:
    print("A + B is not 15. Invalid Operation.")
if A + B != 15:
    result = A + B
    print("A + B =", result)
else:
    result = "A + B equals 15."
if C > A:
    print("C is greater than A. Valid operation.")
else:
    print("C is not greater than A. Invalid operation")
if D < B:
    print("D is less than B. Valid operation")
else:
    print("D is less than B. Invalid operation")
result = A + B
print(result)
result = A - B
print(result)
result = A * D
print(result)
result = C * A
#print(result)
