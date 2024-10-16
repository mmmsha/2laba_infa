# Лабораторная №2
Я создала файл lab2.sh (с расширением bash)

Затем я написала в этом файле следующий скрипт:

![image](https://github.com/user-attachments/assets/dfa90f54-f151-475e-9b20-733171435155)

Этот скриепт работает следующим образом:
- Сначала я указала путь к bash-интерпретатору, используя последовательность shebang (в первой строке скрипта написала #!/bin/bash)
- Объявляется переменная а, в которую записывается ввод пользователя ($1 присваивает первый аргумент скрипта), т.е. а получает на вход данные в виде четырех чисел от 1 до 256, разделенных точками
- Затем вводится массив D2B, который в дальнейшем позволит переводить число из десятичной системы счисления в двоичную.
- После этого я разбиваю строку, которая хранится в а, на массив, в качестве разделителя используя точку
- Затем я пишу цикл for, который берет значение массива под i-тым индексом и заменяет его на запись этого же числа в двоичной системе счисления
- После того, как цикл заканчивается, я с помощью echo вывожу каждое обновленное значение массива по порядку, а между ними ставлю точки

Пример ввода и вывода через терминал:

![image](https://github.com/user-attachments/assets/8e0c6c5c-07f7-4f38-bace-81d354b0132b)
