Добавь еще:
- дерево отрезков vs дерево фенвика
- амортизированная сложность
- базово про Master theorem и как считатть сложность рекурсивных алгоритмов


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

3) Слишком часто в последнее время требуется: 
positive_infinity = float('inf')
еще: float('-inf')

4) дерево. Пока обычное.
DFS и BFS обязательно вставь, можно из задачек с литкода. 
Задачка с валидацией bfs очень показательна

Еще, стоит ли литкод 733 вставлять, как типикал задачу на граф, где не виден явно граф? Не уверен! Ща посмотрю........

Еще, важно бы не только рекурсивные обходы написать, но и итеративные. Хотя рекурсивные внешне пизже, офк.



Еще стоит выложить себе методичку по поиску сложности алгоритма с рекурсией.

6) Стек.
В питоне можно через лист (не оч круто, т.к. траблы динамического массива -- при расширении может возникнуть необходимость копировать все элементы массива).
Рекомендуется реализовывть через collections.deque

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
