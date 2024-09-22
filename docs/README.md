# Math formulas
## Area
- Circle: S = πR²
- Rectangle: S = ab
- Square: S = a²
- Triangle: S = ah/2

## Perimeter
- Circle: P = 2πR
- Rectangle: P = 2(a + b)
- Square: P = 4a
- Triangle: P = a + b + c

# Functions
## Area
### Circle
def area(r):
    Возвращает площадь окружности
        
        Параметры:
                r (float): радиус окружности
        
        Возвращаемое значение:
                square (float): площадь окружности с радиусом r
return math.pi * r * r

r = 4.0
area(4.0) = π * 4.0 * 4.0 = 16π = 50.2654824574

r = 3.5
area(3.5) = π * 3.5 * 3.5 = 12.25π = 38.4845100065

r = 0.0
area(0.0) = π * 0.0 * 0.0 = 0.0

### Rectangle
def area(a, b):
    Возвращает площадь прямоугольника

        Параметры:
                a (float): Сторона a прямоугольника
                b (float): Сторона b прямоугольника
        
        Возвращаемое значение:
                square (float): Площадь прямоугольника со сторонами a и b
    return a * b

a = 1.0, b = 3.0
area(1, 3) = 1 * 3 = 3.0

a = 2.3, b = 5.0
area(2.3, 5.0) = 2.3 * 5.0 = 11.5

a = 0.0 b = 32.33
area(0.0, 32.33) = 0.0 * 32.33 = 0.0

### Square
def area(a):
    Возвращает площадь квадрата

        Параметры:
                a (float): Сторона квадрата
        
        Возвращаемое значение:
                square (float): Площадь квадрата со стороной a
    return a * a

a = 2.0
area(2.0) = 2.0 * 2.0 = 4.0

a = 3.5
area(3.5) = 3.5 * 3.5 = 12.25

a = 0.0
area(0.0) = 0.0 * 0.0 = 0.0

### Trinagle
def area(a, h):
    Возвращает площадь треугольника

        Параметры:
                a (float): Основание треугольника
                h (float): Высота, проведенная к основанию a
                
        Возвращаемое значение:
                square (float): Площадь треугольника с основанием a и высотой h
    return a * h / 2 

a = 2.0, h = 4.0
area(2.0, 4.0) = 2.0 * 4.0 / 2 = 4.0

a = 3.3, h = 6.0
area(3.3, 6.0) = 3.3 * 6.0 / 2 = 9.9

a = 0.0, h = 13.3
area(0.0, 13.3) = 0.0 * 13.3 / 2 = 0.0

## Perimeter
### Circle
def perimeter(r):
    Возвращает периметер окружности

        Параметры:
                r (float): радиус окружности
                
        Возвращаемое значение:
                perimeter (float): периметер окружности с радиусом r
    return 2 * math.pi * r

r = 3.0
perimeter(3.0) = 2 * π * 3.0 = 6π = 18,8495559215

r = 4.3
perimeter(4.3) = 2 * π * 4.3 = 8.6π = 27,0176968209

r = 0.0
perimeter(0.0) = 2 * π * 0.0 = 0.0

### Rectangle
def perimeter(a, b): 
    Возвращает периметер прямоугольника

        Параметры:
                a (float): Сторона a прямоугольника
                b (float): Сторона b прямоугольника
                
        Возвращаемое значение:
                perimeter (float): Периметер прямоугольника со сторонами a и b
    return 2 * (a + b) 

a = 3.0, b = 2.0
perimeter(3.0, 2.0) = 2 * (3.0 + 2.0) = 2 * 5.0 = 10.0

a = 3.3, b = 2.2
perimeter(3.3, 2.2) = 2 * (3.3 + 2.2) = 2 * 5.5 = 11.0

a = 0.0, b = 123.45
perimeter(0.0, 123.45) = 2 * (0.0 + 123.45) = 2 * 123.45 = 246.9

### Square
def perimeter(a):
    Возвращает периметер квадрата
        
        Параметры:
                a (float): Сторона квадрата
        
        Возвращаемое значение:
                perimeter (float): Периметер квадрата со стороной a
    return 4 * a

a = 5.0
perimeter(5.0) = 4 * 5.0 = 20.0

a = 4.3
perimeter(4.3) = 4 * 4.3 = 17.2

a = 0.0
perimeter(0.0) = 4 * 0.0 = 0.0

### Triangle
def perimeter(a, b, c):
    Возвращает периметер треугольника

        Параметры:
                a (float): Сторона a треугольника
                b (float): Сторона b треугольника
                c (float): Сторона c треугольника
        
        Возвращаемое значение:
                perimeter (float): Периметер треугольника со сторонами a, b, c
    return a + b + c

a = 3.0, b = 2.0, c = 4.0
perimeter(3.0, 2.0, 4.0) = 3.0 + 2.0 + 4.0 = 9.0

a = 3.3, b = 2.0, c = 12.54
perimeter(3.3, 2.0, 12.54) = 3.3 + 2.0 + 12.54 = 17.84

a = 1.1, b = 0.0, c = 123.21
perimeter(1.1, 0.0, 123.21) = 1.1 + 0.0 + 123.21 = 124.31

# Commits
- commit 8ba9aeb3cea847b63a91ac378a2a6db758682460 (04.03.21) Message: "Circle and square added"
- commit d078c8d9ee6155f3cb0e577d28d337b791de28e2 (04.03.21) Message: "Docs added"
- commit 0e037543632250b6d4f0d5280f045e23171255d3 (22.09.24) Message: "Add new file" *Add rectangle area and perimeter*
- commit 69ebb978f9dd9ccca95f0ce6267da948751251f3 (22.09.24) Message: "new figure" *Add triangle are and perimeter*
- commit de44ee7e84e424256773d32ee36c2fd64af283d6 (22.09.24) Message: "Fixed bug" *Fixed bug with calculation rectangle perimeter*
- commit bc175c69a311e4b1ce6dfdb0026641068bf47fd2 (22.09.24) Message: "Writting documentaition rectangle.py"
- commit fb9c41366188a9d0c2d0f9069738bddfa2cb011b (22.09.24) Message: "Writting documentaition circle.py"
- commit 5c655967c7b9aae884119ea1deae33bcc0728a58 (22.09.24) Message: "Writting documentaition triangle.py"
- commit 0ed7d31c9383c66a96ecd89a78d324900d1e1468 (22.09.24) Message: "Writting documentaition square.py"
- commit 920ad678b583f212103d4c4f31bc44d5e0cab72b (22.09.24) Message: "Add documentations figures on README.md"