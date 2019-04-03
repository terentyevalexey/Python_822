Попытка реализовать пошаговую стратегию. На данном этапе есть возможность:
1) выбирать произвольное число игроков (юниты единственного типа)
2) event loop, поддерживающий пошаговый режим
3) перемещение ограничено кругом, кастомизируемого в проекте радиуса, в течение одного хода
4) один вариант атаки - fireball, применимый 3 раза за ход, при этом с расстоянием, пройденным шаром, уменьшается урон
5) если на поле остаётся единственный юнит, он объявляется победителем
6) некоторые элементы интерфейса (здоровье и имя около юнита, указание хода, сообщение о победе)

На входе в программу подаются: количество, имена и начальные позиции игроков
Движение осуществляется стрелками на клавиатуре, fireball кидается в направлении нажатия левой клавиши мыши

Программу можно запустить из файла main.py
Requirements: для работы программы необходима библиотека arcade