Добавь еще:
- дерево отрезков vs дерево фенвика
- амортизированная сложность
- базово про Master theorem и как считатть сложность рекурсивных алгоритмов
- мб стоит сделать напоминание себе про лямбда функции? иногда забываю синтаксис. Еще про компараторы (хотя в питоне тут есть нюансы https://stackoverflow.com/questions/12749398/using-a-comparator-function-to-sort и, главное, https://learnpython.com/blog/python-custom-sort-function/ -- вообще, стоит разобраться, почему такую топовую и реально много где нужную концепцию выкинули в python3). Вдохновлено моим собственным решением 692.
- trie. Тоже потом обязательно разберись


Глобально по структуре.
1) папка contests. В ней каждый файл содержит полностью условия (или ссылку на них) и решения всего контеста, а также мой скор.
2) папка data structures, где лежат мои реализации самых важных структур данных на питоне и плюсах. Методы тоже реализованы.
Т.е. в ней есть подпапка на каждую структуру, а в каждой подпапке 2 файла - cpp и py.
Тут же стоит в ноутбуках или мб в отдельной txtшке записать кратно, за какое время можно сделать ту или иную манипуляцию с этой структурой данных.
3) Папка most valuable problems. Они раскинуты по темам.
Типа одна папка - sliding window, 
другая папка - bfs/dfs

## Python
1) dictionary. 
Задача с литкода 3.

2) линдкед лист.
Опять литкод, задача 5.
Без указателей что-то сложно.

Очень часто решается двумя указателями. Пример: https://www.youtube.com/watch?v=XVuQxVej6y8. Имхо, образцовый. Следующую задачу так и решал + с норм питоновским использованием аналога указателей, как в видео.

3) Слишком часто в последнее время требуется: 
positive_infinity = float('inf')
еще: float('-inf')

4) дерево. Пока обычное.
DFS и BFS обязательно вставь, можно из задачек с литкода. 
Задачка с валидацией bfs очень показательна

Еще, стоит ли литкод 733 вставлять, как типикал задачу на граф, где не виден явно граф? Не уверен! Ща посмотрю........

Еще, важно бы не только рекурсивные обходы написать, но и итеративные. Хотя рекурсивные внешне пизже, офк.



Еще стоит выложить себе методичку по поиску сложности алгоритма с рекурсией.

5) Стек.
В питоне можно через лист (не оч круто, т.к. траблы динамического массива -- при расширении может возникнуть необходимость копировать все элементы массива).
Рекомендуется реализовывть через collections.deque

6) очередь.
связь с финансами и биржевым стаканом (тут в начале чет потенциально полезное https://www.youtube.com/watch?v=rUUrmGKYwHw)

7) heap (мб еще BST стоит отдельно выложить и сравнить с heap). Норм описание в карточке на литкоде
https://www.geeksforgeeks.org/heap-queue-or-heapq-in-python/

Имхо, 347 и 692 показательны.

Какая сложность у heapify? O(nlogn)? Все же вроде просто О(n)


XXXX) стоит ли что-то на бинарный поиск выставлять? Мб один раз написанное

Суперважные задачи будто бы:
1) 746. Min Cost Climbing Stairs.
Я пока ее не решил, но выглядит, как сама суть динамического программирования. 
Решил, так и есть, точно идет в мой топ.
2) the number of islands. Очень популярная, т.к. многие задачи на графы строятся на этой. А еще сама по себе очень популярная.
3) 438. Find All Anagrams in a String
это как будто бы основной пример sliding window. 
следующая задача, будто бы тоже супер важна https://leetcode.com/problems/longest-repeating-character-replacement/description/

4) leetcode 394 что-то меня сломала. Хотя она не на конкретную тему мб...
Вообще, она крутая и в чем-то показательная. банальная, но не очень банальная рекурсия, стоит ее отметить. Мб, разве что, не в папку на конкретную тему, а в папку, скажем, "favourite".
Еще, тут весьма ценный трюк со словарем для задачек со скобочками.
Нужно потестить Master theorem на ней.
Решение со стеком тоже очень показательное, его тоже реализую.
______________________________________________
Алгоритмы:
1) bucket sort (стакается с кучей, имхо, 347 и 692 показательны.)
2) вообще, хочу по разным экзотическим сортировкам постепенно пройтись, не только по меинстримным мердж и квик
________________
Вообще работа на будущее. 
1) мб разобраться под капотом. Например с хеш-функцией в dict
