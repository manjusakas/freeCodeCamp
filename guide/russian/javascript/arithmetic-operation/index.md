---
title: Arithmetic Operation
localeTitle: Арифметическая операция
---
В JavaScript существует пять арифметических операторов: `+` , `-` , `*` , `/` и `%` . Операторы сложения, вычитания, умножения, деления и остаток от деления соответственно.

## Сложение

**Синтаксис**

`a + b`

**Использование**
```
 2 + 3          // возвращает 5 
 true + 2       // интерпретирует true как 1 и возвращает 3 
 false + 5      // интерпретирует false как 0 и возвращает 5 
 true + "bar"   // конкатенирует (объединяет) значение boolean и возвращает строку "truebar" 
 5 + "foo"      // конкатенирует строку и число и возвращает строку "5foo" 
 "foo" + "bar"  // конкатенирует строки и возвращает строку "foobar" 
```

_Подсказка:_ оператор [инкремент](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Increment_() ), который используется как удобный шорткат, чтобы увеличенить число на 1.

## Вычитание

**Синтаксис**

`a - b`

**Использование**
```
 2 - 3      // возвращает -1 
 3 - 2      // возвращает 1 
 false - 5  // интерпретирует false как 0 и возвращает -5 
 true + 3   // интерпретирует true как 1 и возвращает 4 
 5 + "foo"  // возвращает NaN (Not a Number) 
```

_Подсказка:_ также есть удобный оператор [декремент](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Decrement_(--) ), который используется как удобный шорткат, когда нужно уменьшить число на 1.

## Умножение

**Синтаксис**

`a * b`

**Использование**
```
 2 * 3                // возвращает 6 
 3 * -2               // возвращает -6 
 false * 5            // интерпретирует false как 0 и возвращает 0 
 true * 3             // интерпретирует true как 1 и возвращает 3 
 5 * "foo"            // возвращает NaN (Not a Number) 
 Infinity * 0         // возвращает NaN 
 Infinity * Infinity  // возвращает Infinity 
```

## Деление

**Синтаксис**

`a / b`

**Использование**
```
 3 / 2                // возвращает 1.5 
 3.0 / 2/0            // возвращает 1.5 
 3 / 0                // возвращает Infinity 
 3.0 / 0.0            // возвращает Infinity 
 -3 / 0               // возвращает -Infinity 
 false / 5            // интерпретирует false как 0 и возвращает 0 
 true / 2             // интерпретирует true как 1 и возвращает 0.5 
 5 + "foo"            // возвращает NaN (Not a Number) 
 Infinity / Infinity  // возвращает NaN 
```

## Остаток от деления

**Синтаксис**

`a % b`

**Использование**
```
 3 % 2          // возвращает 1 
 true % 5       // интерпретирует true как 1 и возвращает 1 
 false % 4      // интерпретирует false как 0 и возвращает 0 
 3 % "bar"      // возвращает NaN 
```

## Инкремент

**Синтаксис**

`a++ или ++a`

**Использование**
```
// как постфикс 
 x = 3;  // объявление переменной 
 y = x++;        // y = 4, x = 3 
 
 // как префикс
 var a = 2; 
 b = ++a; // a = 3, b = 3 
```

## Декремент

**Синтаксис**

`a-- или --a`

**Использование**
```
// как постфикс 
 x = 3;  // объявление переменной 
 y = x--;        // y = 3, x = 3 
 
 // как префикс 
 var a = 2; 
 b = --a; // a = 1, b = 1 
```

_!Важно!_ Как вы, наверное, заметили, вы **не можете** выполнять какие-либо операции с `Infinity` .

Источник: замечательный [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators) .
