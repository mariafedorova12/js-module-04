# js-module-04

01.
Дополни код так, чтобы в переменной result был результат выполнения функции makePizza, а в переменной pointer была ссылка на функцию makePizza.

Тесты
Объявлена функция makePizza.
Объявлена переменная result.
Значение переменной result это строка 'Ваша пицца готовится, ожидайте.'.
Значение переменной result получено с помощью вызова функции.
Объявлена переменная pointer.
Значение переменной pointer это ссылка на функцию makePizza.

02.
Дополни функцию makeMessage так, чтобы она ожидала вторым параметром (параметр callback) колбэк-функцию и возвращала ее вызов. Функция deliverPizza или makePizza будет передаваться как колбэк и ожидать аргументом имя готовой доставляемой пиццы.

Тесты
Объявлена функция deliverPizza.
Объявлена функция makePizza.
Объявлена функция makeMessage.
Функция makeMessage принимает два параметра, названые согласно задания, pizzaName и callback.
Вызов makeMessage('Роял гранд', makePizza) возвращает строку 'Пицца Роял гранд готовится, ожидайте...'.
Вызов makeMessage('Ультрасыр', deliverPizza) возвращает строку 'Доставляем пиццу Ультрасыр.'.

03.
Дополни второй вызов функции makePizza(pizzaName, callback), передав вторым аргументом инлайн колбэк-функцию eatPizza(pizzaName), которая логирует строку 'Едим пиццу <имя пиццы>'.

Тесты
Объявлена функция makePizza.
Функция makePizza принимает два параметра.
Вторым аргументом при вызове makePizza('Ультрасыр') передана функция eatPizza с единственным параметром pizzaName.
04.
05.
06.
07.
08.
09.
10.
