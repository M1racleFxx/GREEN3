# Дз 3
## Задача 1
```
import math

def distance (x1, y1, x2, y2):
    x = x2-x1
    y = y2-y1
    
    pifagor = math.sqrt(x*x + y*y)
    
    return (pifagor)

distance (10, 20, 20, 30)
```
## Задача 2
```
def power(a, n):
    b = a
    for i in range(n - 1):
        b = b * a

    return b


power(3, 2)
```
## Задача 3
```
def capitalize(word):
    first_lower = word[0]
    return first_lower.upper() + word[1:]


word = "hello"
print(capitalize(word))
```
## Задача 4
```
def factorial(n):
    x = 1
    for i in range(1, n + 1):
        x = x * i

    return x

print(factorial(5))
```
## Задача 5
```
def power(a, n):
    if n == 0:
        return 1
    else:
        return a * power(a, n - 1)

result = power(2, 3)
print(result)
```
## Задача 6
```
def print_reverse():
    number = int(input("Введите число (0 для завершения): "))
    if number == 0:
        return
    print_reverse()
    print(number)

print_reverse()
```
