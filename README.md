# Методы работы со строками в JavaScript

---

## _Основные методы_

### 1) _charAt_: возвращает символ по указанному индексу.
```Javascript
let text = "Привет, мир!";
console.log(text.charAt(0)); // "П"
```


### 2) _concat_: объединяет две или более строк и возвращает новую строку.
```Javascript
let greeting = "Привет";
let name = "Мир";
let message = greeting.concat(", ", name, "!");
console.log(message); // "Привет, Мир!"
```


### 3) _includes_: проверяет, содержится ли подстрока в строке, возвращая true или false
```Javascript
let text = "Я люблю JavaScript";
console.log(text.includes("люблю")); // true
```


###  4) _indexOf_: возвращает индекс первого вхождения подстроки или -1, если подстрока не найдена.
```Javascript
let text = "Я люблю JavaScript";
console.log(text.indexOf("люблю")); // 2
```


###  5) _replace_: заменяет первое вхождение подстроки на новую строку.
```Javascript
let text = "Я люблю JavaScript";
let newText = text.replace("люблю", "обожаю");
console.log(newText); // "Я обожаю JavaScript"
```

![slide-11](https://github.com/user-attachments/assets/035c219b-3cbf-4a1b-90c7-87740379776c)



###  6) _slice_: извлекает часть строки от start до end (не включая end).
```Javascript
let text = "Привет, мир!";
let substring = text.slice(0, 6);
console.log(substring); // "Привет"
```


###  7) _split_: разбивает строку на массив подстрок, используя разделитель.
```Javascript
let text = "яблоко,банан,вишня";
let fruits = text.split(",");
console.log(fruits); // ["яблоко", "банан", "вишня"]
```

###  8) _toLowerCase()_: преобразует все символы строки в нижний регистр.
```Javascript
let text = "ПрИвЕт, МиР!";
let lowerText = text.toLowerCase();
console.log(lowerText); // "привет, мир!"
```

###  9) _toUpperCase()_: преобразует все символы строки в верхний регистр.
```Javascript
let text = "ПрИвЕт, МиР!";
let upperText = text.toUpperCase();
console.log(upperText); // "ПРИВЕТ, МИР!"
```

###  10) _trim()_: удаляет пробелы с начала и конца строки.
```Javascript
let text = "  Привет, мир!  ";
let trimmedText = text.trim();
console.log(trimmedText); // "Привет, мир!"
```
