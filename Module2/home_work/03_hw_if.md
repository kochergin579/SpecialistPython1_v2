## "Клетки шахматной доски"

### Задание

Имеем стандартное поле шахматной доски размеров 8x8

![board.png](img/board.png)

Даны координаты двух клеток на шахматной доске.

Определить, одинакового ли цвета клетки?

### Формат входных данных

Даны четыре целые числа в диапазоне [1, 8]

### Формат выходных данных

Вывести "Да", если клетки с заданными координатам одинакового цвета, и "Нет", если разного.

### Решение задачи

```python
# TODO: you code here...
```
x1 = int(input("Координата по горизонтали 1: "))
y1 = int(input("Координата по вертикали 1: "))
x2 = int(input("Координата по горизонтали 2: "))
y2 = int(input("Координата по вертикали 2: "))
if (x1 + y1 + x2 + y2)%2 ==0:
    print("yes")
else:
    print("no")
---

### Подсказки

<details>
<summary>Подсказка-1</summary>
Условие для проверки четности числа:

```python
n % 2 == 0
```

</details>

<details>
<summary>Подсказка-2</summary>
Сумма двух нечетных чисел, всегда четная.
</details>
