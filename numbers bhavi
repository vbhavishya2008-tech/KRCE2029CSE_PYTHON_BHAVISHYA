# 1. Prime Number
n = int(input())
count = 0

for i in range(1, n + 1):
    if n % i == 0:
        count += 1

if count == 2:
    print("Prime")
else:
    print("Not Prime")


# 2. Perfect Number
n = int(input())
sum = 0

for i in range(1, n):
    if n % i == 0:
        sum += i

if sum == n:
    print("Perfect")
else:
    print("Not Perfect")


# 3. Armstrong Number
n = int(input())
temp = n
sum = 0
digits = len(str(n))

while temp > 0:
    d = temp % 10
    sum += d ** digits
    temp //= 10

if sum == n:
    print("Armstrong")
else:
    print("Not Armstrong")


# 4. Strong Number
n = int(input())
temp = n
sum = 0

while temp > 0:
    d = temp % 10
    fact = 1

    for i in range(1, d + 1):
        fact *= i

    sum += fact
    temp //= 10

if sum == n:
    print("Strong")
else:
    print("Not Strong")


# 5. Palindrome Number
n = int(input())
temp = n
rev = 0

while temp > 0:
    d = temp % 10
    rev = rev * 10 + d
    temp //= 10

if rev == n:
    print("Palindrome")
else:
    print("Not Palindrome")


# 6. Automorphic Number
n = int(input())
square = n * n

if str(square).endswith(str(n)):
    print("Automorphic")
else:
    print("Not Automorphic")


# 7. Harshad Number
n = int(input())
temp = n
sum = 0

while temp > 0:
    sum += temp % 10
    temp //= 10

if n % sum == 0:
    print("Harshad")
else:
    print("Not Harshad")


# 8. Neon Number
n = int(input())
square = n * n
sum = 0

while square > 0:
    sum += square % 10
    square //= 10

if sum == n:
    print("Neon")
else:
    print("Not Neon")


# 9. Spy Number
n = int(input())
temp = n
sum = 0
product = 1

while temp > 0:
    d = temp % 10
    sum += d
    product *= d
    temp //= 10

if sum == product:
    print("Spy")
else:
    print("Not Spy")


# 10. Duck Number
n = input()

if "0" in n:
    print("Duck")
else:
    print("Not Duck")


# 11. Disarium Number
n = int(input())
temp = n
digits = len(str(n))
sum = 0

while temp > 0:
    d = temp % 10
    sum += d ** digits
    digits -= 1
    temp //= 10

if sum == n:
    print("Disarium")
else:
    print("Not Disarium")


# 12. Happy Number
n = int(input())

while n != 1 and n != 4:
    sum = 0

    while n > 0:
        d = n % 10
        sum += d * d
        n //= 10

    n = sum

if n == 1:
    print("Happy")
else:
    print("Not Happy")


# 13. Abundant Number
n = int(input())
sum = 0

for i in range(1, n):
    if n % i == 0:
        sum += i

if sum > n:
    print("Abundant")
else:
    print("Not Abundant")


# 14. Deficient Number
n = int(input())
sum = 0

for i in range(1, n):
    if n % i == 0:
        sum += i

if sum < n:
    print("Deficient")
else:
    print("Not Deficient")


# 15. Circular Prime
n = int(input())
s = str(n)
length = len(s)
circular = True

for i in range(length):
    num = int(s[i:] + s[:i])

    if num < 2:
        circular = False
        break

    for j in range(2, int(num ** 0.5) + 1):
        if num % j == 0:
            circular = False
            break

    if not circular:
        break

if circular:
    print("Circular Prime")
else:
    print("Not Circular Prime")
