# Пользовательская документация geometric_lib
## Описание проекта
Проект представляет собой набор функций для нахождения площади и периметра различных фигур(круга, прямоугольника,
квадрата и треугольника).
## Описание функций
### circle.py
```
import math ```Подключаем библиотеку, которая содержит набор функций для выполнения математических, тригонометрических и логарифмических операций.```
  
  
def area(r):  ```Функция для нахождения площади круга.```
    return math.pi * r * r  
  
  
def perimeter(r): ```Функция для нахождения периметра круга.``` 
    return 2 * math.pi * r
```
Пример:
Входные данные: r = 3
```
1. def area(r)
```
Возвращаемое значение: 28.274333882308138
```
2. def perimeter(r)
```
Возвращаемое значение: 18.84955592153876

### rectangle.py


```
def area(a, b):  ```Функция для нахождения площади прямоугольника. ```
    return a * b  
  
def perimeter(a, b):  ```Функция для нахождения периметра прямоугольника.```
    return 2 * (a + b)
```
    
Пример:
Входные данные: a = 3, b = 4
```
1. def area(a, b)
```
Возвращаемое значение: 12
```
2. def perimeter(a, b)
```
Возвращаемое значение: 14

### square.py

```
def area(a):  ```Функция для нахождения площади квадрата.```
    return a * a  
  
  
def perimeter(a):  ```Функция для нахождения периметра квадрата.```
    return 4 * a
```
Пример:
Входные данные: a = 3
```
1. def area(a)
```
Возвращаемое значение: 9
```
2. def perimeter(a)
```
Возвращаемое значение: 12

### triangle.py
```
def area(a, h):  ```Функция для нахождения площади треугольника.```
    return a * h / 2  
  
def perimeter(a, b, c):  ```Функция для нахождения периметра треугольника.```
    return a + b + c
```
Пример:
Входные данные: a = 3, b = h = 4, c = 5
```
1. def area(a, h)
```
Возвращаемое значение: 6
```
2. def perimeter(a, b, c)
```
Возвращаемое значение: 12

## История изменения проекта

1. Коммит с сообщением о создании файла rectangle.py:
```
commit ef6242ddd77263b7cdae5c286bc899cd9b65839d
Author: Kira <kiravrks@gmail.com>
Date:   Sun Sep 29 21:08:37 2024 +0300

    new file rectangle. py
```
2. Коммит с сообщением об устранении ошибки в файле rectangle.py:
```
commit f3c66e34797e8da8e4b4f14e125cf61d6b98cba9 (HEAD -> new_branch)
Author: Kira <kiravrks@gmail.com>
Date:   Sun Sep 29 22:15:30 2024 +0300

    error edited
```
```
diff --git a/rectangle.py b/rectangle.py
index 771a133..d670a80 100644
--- a/rectangle.py
+++ b/rectangle.py
@@ -2,4 +2,4 @@ def area(a, b):
     return a * b

 def perimeter(a, b):
-    return a + b
\ No newline at end of file
+    return 2 * (a + b)
```