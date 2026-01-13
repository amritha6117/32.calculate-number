# 32.calculate-number
s = input("Input a string: ")

d = l = 0

for c in s:
    if c.isdigit():
        d += 1
    elif c.isalpha():
        l += 1

print("Letters:", l)
print("Digits:", d)
OUTPUT:
Input a string: 5
Letters: 0
Digits: 1
