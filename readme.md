## JavaScript про ECMAScript
### Урок 1. Функциональный Javascript

![image](homework.png)\
Домашнее задание: [index.html](index.html), [homework.js](homework.js)

1. Дан массив `const arr = [1, 5, 7, 9]` с помощью `Math.min` и spread оператора, найти минимальное число в массиве, решение задание должно состоять из одной строки.
2. Напишите функцию `createCounter`, которая создает счетчик и возвращает объект с двумя методами: `increment` и `decrement`.
   - Метод `increment` должен увеличивать значение счетчика на 1
   - Метод `decrement` должен уменьшать значение счетчика на 1.
   - Значение счетчика должно быть доступно только через методы объекта, а не напрямую.
3. Напишите рекурсивную функцию `findElementByClass`, которая принимает корневой элемент дерева DOM и название класса в качестве аргументов и возвращает первый найденный элемент с указанным классом в этом дереве.\
   Пример:
   ```js
   const rootElement = document.getElementById('root');
   const targetElement = findElementByClass(rootElement, 'my-class');
   console.log(targetElement);
   ```