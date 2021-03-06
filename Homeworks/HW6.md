### Домашнее задание №6 **Оцениваемое (прежде чем приступить обязательно ознакомьтесь с [правилами оцениваемых домашних работ из этого файла](https://github.com/ancatmara/python-for-dh/blob/master/Classes/3/О_дз.md))**

При наличии причины можно обсудить дедлайн в индивидуальном порядке с @NickVeld (telegram).

Выполняется работа **строго** в репозитории **python-dh-hw** в файле **HW6.ipynb**, лежащем в корне репозитория: 

Прежде всего следует изучить [содержимое папки про третий семинар](https://github.com/ancatmara/python-for-dh/tree/master/Classes/3), все файлы кроме файла с семинара (там есть описание по установке необходимых программ для сдачи ДЗ ([Intro.ipynb](https://github.com/ancatmara/python-for-dh/blob/master/Classes/3/Intro.ipynb)) - это предписания по выполнению текущей и будущих домашних работ, изучите их **предельно внимательно**. (В том числе пример сдачи).

Имейте ввиду, что ваши программы должны работать при любом допустимом вводе, а не только выбранном вами.

Решите три задачи:

#### 1. [6 баллов] Дан набор слов "абракадабра фокус покус десятка за курс немедленно появись":

* Необходимо написать функцию, которая выделяет все символьные биграммы в этом наборе слов и возвращает их список. Символьные биграммы -- это пары стоящих рядом букв, например, "ра", "ку". (Но это не буквы разделенные пробелами или пара из буквы и пробела!) Выведите (применить функцию print) этот список.

* Создать словарь, где ключами будут полученные биграммы, а значениями — их количество в во введенном тексте

* Проитерироваться по словарю, пока не встретится биграмма из двух одинаковых букв. На каждой итерации надо вывести (применить функцию print) рассматриваемую биграмму, и количество раз, которое она встретилось.

#### 2. [4 балла] Даны два слова, ваша программа должна проверять является ли второе слово обратной записью первого слова.

Например, вы выбрали слова `"кот"` и `"ток"`, тогда программа должна показать:
```YES```.

Например, вы выбрали слова `"белый"` и `"черный"`, тогда программа должна покзать:
```NO```.

**Примечание**: Для демонстрации работы своей программы, нужно запустить программу на одной паре слов, для которой ответ `YES`, а потом для второй пары, для которой ответ `NO`. (Чтобы это было легко и красиво сделать, стоит программу оформить в виде функции.)

#### 3. [5 баллов] Бонусная задача -- игра "Виселица":

* Задать список слов, которые будут использоваться для игры (внутри скрипта). Лучше длинные, штук 5-10 хватит 

* При запуске программа должна случайным образом выбирать из списка и говорить пользователю что-то на подобии "у вас есть N попыток, чтобы угадать слово из X букв" и выводить строчку из _ по количеству букв в слове, арзделенными пробелами. Количество попыток нужно выбрать самостоятельно, оно должно всегда быть одинаковым

* Если пользователь угадал букву, то программа должна заменять _ в соответствующем месте на угаданную букву

* Программа должна выдавать разные сообщения в зависимости от того, угадал пользователь букву или нет, а также если он уже вводил эту букву или если введенный символ — не буква

* Если названной буквы нет в слове, то программа должна рисовать деталь человечка. Обратите внимание, что количество деталей должно быть равно количеству попыток! Как будет выглядеть картинка, выбирайте сами

**Примечание**: Для ввода обязательно используйте функцию `input()`, что позволит получить строку ввода.

**Примечание**: Отдельным одним баллом будет оценено умение программы ругаться, если ввели не одну букву, а что-то иное, и согласовывать числительные с существительными, то есть выводить сообщения не "Осталось попыток: 5", а "Осталось 5 попыток, осталась 1 попытка" и т.п.

После решения задач необходимо выложить решение в Github. и проверить, что вы видите ваше решение по ссылке `https://github.com/*ваш username на github*/python-dh-hw/blob/master/HW6.ipynb`

Убедитесь, что по этой ссылке можно увидеть результат работы программ, хотя бы по одному допустимому вводу.

В этом и в следующих заданиях коммиты следует делать через консольный интерфейс, а сообщения коммитов должны быть осмысленными (иначе в оцениваемых работах баллы будут снижаться, учим хорошему тону и полезному навыку).
