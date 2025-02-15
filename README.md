# Методы работы со строками в JavaScript

---

## Введение
JavaScript предоставляет богатый набор методов для работы со строками, позволяющих выполнять операции по извлечению, поиску, замене и преобразованию текста. Этот набор инструментов поможет вам создавать динамичные и эффективные приложения. :rocket:

---

## Основные методы

### 1) charAt(index): возвращает символ по указанному индексу.
```Javascript
let text = "Привет, мир!";
console.log(text.charAt(0)); // "П"
```


### 2) concat(str1, str2, ...): объединяет две или более строк и возвращает новую строку.
```Javascript
let greeting = "Привет";
let name = "Мир";
let message = greeting.concat(", ", name, "!");
console.log(message); // "Привет, Мир!"
```


### 3) includes(substring): проверяет, содержится ли подстрока в строке, возвращая true или false
```Javascript
let text = "Я люблю JavaScript";
console.log(text.includes("люблю")); // true
```


###  4) indexOf(substring): возвращает индекс первого вхождения подстроки или -1, если подстрока не найдена.
```Javascript
let text = "Я люблю JavaScript";
console.log(text.indexOf("люблю")); // 2
```


###  5) replace(searchValue, newValue): заменяет первое вхождение подстроки на новую строку.
```Javascript
let text = "Я люблю JavaScript";
let newText = text.replace("люблю", "обожаю");
console.log(newText); // "Я обожаю JavaScript"
```


###  6) slice(start, end): извлекает часть строки от start до end (не включая end).
```Javascript
let text = "Привет, мир!";
let substring = text.slice(0, 6);
console.log(substring); // "Привет"
```


###  7) split(separator): разбивает строку на массив подстрок, используя разделитель.
```Javascript
let text = "яблоко,банан,вишня";
let fruits = text.split(",");
console.log(fruits); // ["яблоко", "банан", "вишня"]
```


###  8) toLowerCase(): преобразует все символы строки в нижний регистр.
```Javascript
let text = "ПрИвЕт, МиР!";
let lowerText = text.toLowerCase();
console.log(lowerText); // "привет, мир!"
```


###  9) toUpperCase(): преобразует все символы строки в верхний регистр.
```Javascript
let text = "ПрИвЕт, МиР!";
let upperText = text.toUpperCase();
console.log(upperText); // "ПРИВЕТ, МИР!"
```


###  10) trim(): удаляет пробелы с начала и конца строки.
```Javascript
let text = "  Привет, мир!  ";
let trimmedText = text.trim();
console.log(trimmedText); // "Привет, мир!"
```
