Напишите программу, которая принимает
на вход цифру, обозначающую день недели,
и проверяет, является ли этот день выходным.
Пример:
- 6 -> да
- 7 -> да
- 1 -> нет
~~~
sat = 6
sun = 7
day_week = int(input('Введите цыфру дня недели: '))
if day_week == 6 or day_week == 7:
    print('да')
else:
    print('нет')~~~
    
Напишите программу, которая принимает
на вход координаты точки (X и Y), 
причём X ≠ 0 и Y ≠ 0 и выдаёт номер 
четверти плоскости, в которой находится
эта точка (или на какой оси она находится).
Пример:
- x=34; y=-30 -> 4
- x=2; y=4-> 1
- x=-34; y=-30 -> 3
 = int(input('Введиет координату точки X: '))
y = int(input('Введите координату точки Y: '))
if x == 0 and y == 0:
    print('Введите другие координаты X и Y больше нуля')
elif x > 0 and y > 0:
    print(1)
elif x > 0 and y < 0:
    print(2)
elif x < 0 and y < 0:
    print(3)
elif x == 0:
    print('Y')
elif y == 0:
    print('X')        
else:
    print(4)                