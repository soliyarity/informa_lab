#Задание 1
```
print("Информатика — наука об информации")
```
#Задание 2
```
b = int(input())
print(b * 1024)
```
#Задание 3
```
b = int(input())
print(b * 8)
```
#Задание 4
```
a = int(input())
b = int(input())

print((a * b), "- Площадь")
print(2 * (a + b), "- Периметр")
```
#Задание 5
```
n = int(input())

if n % 2 == 0:
    print("Чётное")
else:
    print("Нечётное")
```
#Задание 6
```
a = int(input())
b = int(input())
c = int(input())

print(max(a, b, c))
```
#Задание 7
```
n = int(input())
s = 0

for i in range(1, n + 1):
    s += i

print(s)
```
#Задание 8
```
for n in [8, 16, 32]:
    print(2 ** n)
```
#Задание 9
```
n = int(input())

for i in range(1, 11):
    print(n, "*", i, "=", n * i)
```
#Задание 10
```
text = input()

print(len(text), "- количество символов")
print(len(text) * 8, "- бит")
```
#Задание 12
```
nums = [12, 7, 25, 3, 18]

print(sum(nums))
print(sum(nums) / len(nums))
```
#Задание 13
```
nums = [5, -2, 8, 0, -7, 14]
positive = [x for x in nums if x > 0]
print(positive)
```
#Задание 14
```
c = float(input())
f = c * 9 / 5 + 32
print(f)
```
#Задание 15
```
passwooord = "12345"
entered = input()

if entered == password:
    print("Доступ разрешён")
else:
    print("Доступ запрещён")
```
