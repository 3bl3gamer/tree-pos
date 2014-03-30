Tree nodes position calculator
==============================

## Попытка номер раз

`1.html`

![First version](https://raw.githubusercontent.com/3bl3gamer/tree-pos/master/1.png "First version")

Более ранний, простой и медленный способ. Суть проста:
 * есть ноды (`Node`) с координатами и списком дочерних нод
 * каждая нода притягивается ко всем дочерним нодам, а их притягивает к себе (`compressTree`, [по Верле](http://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%92%D0%B5%D1%80%D0%BB%D0%B5))
 * каждая нода отталкивается от всех нод дерева (вообще от всех, `pushEachNodeFromWholeTree`, по тому же Верле)

Особенно медленный последний пункт.


## Попытка номер два

`2.html`

![Second version](https://raw.githubusercontent.com/3bl3gamer/tree-pos/master/2.png "Second version")
