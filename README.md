#### Основные требования

- Задачи ориентированы на логическое мышление;
- На решение дается полтора часа;
- Использовать любой онлайн редактор, окружение на рабочих машинах не ждем. (https://www.w3schools.com/php/phptryit.asp?filename=tryphp_compiler);
- Результат решения каждого задания оформить в отдельный файл .php, все решения запаковать в архив, название архива Ваша Фамилия Имя;
- Удачи;


#### 1.Возводить в квадраный корень или не возводить:
	
Напишите метод, который будет получать массив целых чисел в качестве параметра и будет обрабатывать каждое число из этого массива.

Вернуть новый массив с обработкой каждого элемента входного массива по следующему правилу - eсли число имеет целый квадратный корень, вернуть корень числа, иначе возведите число в квадрат.

**Пример входных и выходных параметров:**

[4,3,9,7,2,1] -> [2,9,3,49,4,1]

**Важно:**

Входной массив всегда будет содержать только положительные числа и никогда не будет пустым или нулевым.

```php
function squareOrSquareRoot($array) {
  // Пишите свой код здесь
}
```

#### 2.Не дай мне пять

В этом задании Вы получаете начальный номер последовательности и конечный номер, должны вернуть количество всех чисел, кроме номеров содержащих цифру 5 в нем. Начальный и конечный номер включительно!

**Пример входных и выходных параметров:**

1,9 -> 1,2,3,4,6,7,8,9 -> Result 8

4,17 -> 4,6,7,8,9,10,11,12,13,14,16,17 -> Result 12

**Важно:**

Результат может содержать пятерки.

Начальный номер всегда будет меньше конечного. Оба числа могут быть и отрицательными!

Возможно, кто-то из вас найдет простое чисто математическое решение.

```php
function dont_give_me_five($start, $end) {
  // Пишите свой код здесь
}
```

#### 3. Считай пальцами

На каждой руке Виктора по пять пальцев, когда он был ребенком, у него уже было 5 пальцев(на одной руке). Он часто считал число с помощью пальцев.

**Он считает так:**
```
а - Большой палец
б - Указательный палец
в - Средний палец
г - Безымянный палец
е - Мизинец

 a  b  c  d  e
--------------
 1  2  3  4  5
 9  8  7  6
   10 11 12 13
17 16 15 14
   18 19 20 21
.. .. .. ..
   .. .. .. ..
```

Вопрос: когда Виктор считает до числа `n`, какой палец соответствует?

Завершите функцию, которая принимает целое число и возвращает название пальца, на котором закончится счет: `Большой палец`, `Указательный палец`, `Средний палец`, `Безымянный палец` или `Мизинец`.

**Пример входных и выходных параметров:**

```
10 => "Указательный палец"
20 => "Безымянный палец"
30 => "Безымянный палец"
50 => "Указательный палец"
100 => "Безымянный палец"
1000 => "Указательный палец"
10000 => "Указательный палец"
```

```
function which_finger($n) {
  // Пишите свой код здесь
}
```
