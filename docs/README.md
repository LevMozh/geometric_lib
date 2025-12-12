
# Geometric Library - Документация

## Общее описание

Библиотека geometric_lib содержит функции для вычисления площади и периметра геометрических фигур: круга, прямоугольника, квадрата, треугольника.

В библиотеку входят файлы:

* `circle.py` - функции для круга
* `rectangle.py` - функции для треугольника
* `square.py` - функции для квадрата
* `triangle.py` - функции для треугольника

## Описание функций с примерами вызова

### circle.py

#### area(r)

По заданному радиусу вычисляет площадь круга

*Параметры:*
* `r` (float) - радиус круга

*Возвращает:*
* float - площадь круга

*Пример:*
```python
from circle import area
a = area(8.0)
print(a) #201.0619298297468
```

#### perimeter(r)

По заданному радиусу вычисляет периметр круга

*Параметры:*
* `r` (float) - радиус окружности

*Возвращает:*

* float - длина окружности

*Пример:*

```python
from circle import perimeter
p = perimeter(8.0)
print(p) #50.26548245743669
```
### rectangle.py

#### area(a, b)

По заданным сторонам вычисляет площадь прямоугольника

*Параметры:*
* `a` (float) - ширина прямоугольника

* `b` (float) - высота прямоугольника

*Возвращает:*
* float - площадь прямоугольника

*Пример:*
```python
from rectangle import area
a = area(7.0, 10.0)
print(a) #70.0
```

#### perimeter(a, b)

По заданным сторонам вычисляет периметр прямоугольника

*Параметры:*

* `a` (float) - ширина прямоугольника

* `b` (float) - высота прямоугольника

*Возвращает:*

* float - периметр прямоугольника

*Пример:*

```python
from rectangle import perimeter
a = perimeter(7.0, 10.0)
print(a) #34.0
```
### square.py

#### area(a)

По заданному радиусу вычисляет площадь квадрата

*Параметры:*
* `a` (float) - сторона квадрата

*Возвращает:*
* float - площадь квадрата

*Пример:*
```python
from square import area
a = area(10.0)
print(a) #100.0
```

#### perimeter(a)

По заданному радиусу вычисляет периметр квадрата

*Параметры:*
* `a` (float) - сторона квадрата

*Возвращает:*

* float - периметер квадрата

*Пример:*

```python
from square import perimeter
p = perimeter(10.0)
print(p) #40.0
```
### triangle.py

#### area(a, h)

По основанию и высоте вычисляет площадь треугольника

*Параметры:*
* `a` (float) - сторона треугольника
* `h` (float) - высота треугольника, проведенная к стороне `a`

*Возвращает:*
* float - площадь треугольника

*Пример:*
```python
from triangle import area
a = area(3.0, 6.0)
print(a) #9.0
```

#### perimeter(a, b, c)

    По заданным сторонам вычисляет периметр треугольника

*Параметры:*
* `a` (float) - первая сторона треугольника
* `b` (float) - вторая сторона треугольника
* `c` (float) - третья сторона треугольника

*Возвращает:*

* float - периметер треугольника

*Пример:*

```python
from triangle import perimeter
p = perimeter(3.0, 4.0, 5.0)
print(p) #12.0
```

## Истоия изменения библиотеки


| Хеш коммита | Ветка | Текст коммита |
|-------------|-------|-------------------|
| `a9bb8ff` | new_features_501403 | new file added, fixed error |
| `ibfedi6` | new_features_501403 | added new file |
| `86edbic` | origin/release | L-05: Update Docs. Add user agreement info |
| `438b89a` | - | L-05: Add user agreement |
| `6ad0962` | - | L-03: Docs added |
| `3049431` | origin/feature | L-04: Add rectangle.py |
| `b5b0fae` | origin/develop | L-04: Update docs for calculate.py |
| `d76db2a` | origin/develop | L-04: Add calculate.py |
| `51c40eb` | origin/develop | L-04: Doc updated for triangle |
| `d080c78` | origin/develop | L-04: Triangle added |
| `d078c8d` | origin/main, origin/HEAD, main | L-03: Docs added |
| `8ba9aeb` | - | L-03: Circle and square added |