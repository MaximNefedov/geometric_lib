# Geometric Lib

Библиотека на Python для вычисления площади и периметра геометрических фигур: круга, прямоугольника, квадрата и треугольника.

## Математические формулы

| Фигура | Площадь | Периметр |
| :--- | :--- | :--- |
| Круг | $S = \pi R^2$ | $P = 2 \pi R$ |
| Прямоугольник | $S = a \cdot b$ | $P = 2(a + b)$ |
| Квадрат | $S = a^2$ | $P = 4a$ |
| Треугольник | $S = \frac{a \cdot h}{2}$ | $P = a + b + c$ |

---

## Описание функций и примеры вызова

### Круг (`circle.py`)

- `area(r)` — принимает радиус `r`, возвращает площадь круга.
  ```python
  import circle

  print(circle.area(5))  # 78.53981633974483
  ```

- `perimeter(r)` — принимает радиус `r`, возвращает длину окружности.
  ```python
  import circle

  print(circle.perimeter(5))  # 31.41592653589793
  ```

### Прямоугольник (`rectangle.py`)

- `area(a, b)` — принимает стороны `a` и `b`, возвращает площадь прямоугольника.
  ```python
  import rectangle

  print(rectangle.area(3, 4))  # 12
  ```

- `perimeter(a, b)` — принимает стороны `a` и `b`, возвращает периметр прямоугольника.
  ```python
  import rectangle

  print(rectangle.perimeter(3, 4))  # 14
  ```

### Квадрат (`square.py`)

- `area(a)` — принимает сторону `a`, возвращает площадь квадрата.
  ```python
  import square

  print(square.area(4))  # 16
  ```

- `perimeter(a)` — принимает сторону `a`, возвращает периметр квадрата.
  ```python
  import square

  print(square.perimeter(4))  # 16
  ```

### Треугольник (`triangle.py`)

- `area(a, h)` — принимает основание `a` и высоту `h`, возвращает площадь треугольника.
  ```python
  import triangle

  print(triangle.area(6, 4))  # 12.0
  ```

- `perimeter(a, b, c)` — принимает стороны `a`, `b`, `c`, возвращает периметр треугольника.
  ```python
  import triangle

  print(triangle.perimeter(3, 4, 5))  # 12
  ```

---

## История изменений

| Хеш | Автор | Дата | Сообщение коммита |
| :--- | :--- | :--- | :--- |
| `e3e1156` | MaximNefedov | 2026-10-03 | Добавлены комментарии в triangle.py |
| `a9c0457` | MaximNefedov | 2026-10-03 | Добавлены комментарии в square.py |
| `a21f009` | MaximNefedov | 2026-10-03 | Добавлены комментарии в rectangle.py |
| `3744302` | MaximNefedov | 2026-10-03 | Добавлены комментарии в circle.py |
| `4507d5c` | MaximNefedov | 2026-10-03 | Fix rectangle perimeter calculation error (also add triangle.py) |
| `8af9b23` | MaximNefedov | 2026-10-03 | Add rectangle.py with area and perimeter functions |
| `d078c8d` | smartiqa | 2021-03-04 | L-03: Docs added |
| `8ba9aeb` | smartiqa | 2021-03-04 | L-03: Circle and square added |