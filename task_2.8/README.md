### Побочная диагональ

**Описание**  
Напишите программу, которая создаёт матрицу размером \( n \times n \) и заполняет её по следующему правилу:
- Числа на побочной диагонали равны `1`.
- Числа, стоящие выше побочной диагонали, равны `0`.
- Числа, стоящие ниже побочной диагонали, равны `2`.

Побочная диагональ — это диагональ, идущая из правого верхнего в левый нижний угол матрицы.

#### Формат входных данных
На вход программе подаётся одно натуральное число \( n \) — количество строк и столбцов в матрице.

#### Формат выходных данных
Программа должна вывести матрицу в соответствии с описанными условиями. Числа в строке должны быть разделены одним пробелом.

#### Примеры

**Пример 1**

Входные данные:
```
4
```

Выходные данные:
```
0 0 0 1
0 0 1 2
0 1 2 2
1 2 2 2
```

**Пример 2**

Входные данные:
```
2
```

Выходные данные:
```
0 1
1 2
```

**Пример 3**

Входные данные:
```
3
```

Выходные данные:
```
0 0 1
0 1 2
1 2 2
```