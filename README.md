# Methods in JS
## В JavaScript строки являются примитивными и неизменяемыми значениями. Это означает, что все методы строк возвращают новые строки, не изменяя оригинал. Ниже представлены некоторые из наиболее часто используемых методов строк:

### charAt(index): возвращает символ по указанному индексу.
```Javascript
let text = "Привет, мир!";
console.log(text.charAt(0)); // "П"
```

### concat(str1, str2, ...): объединяет две или более строк и возвращает новую строку.
```Javascript
let greeting = "Привет";
let name = "Мир";
let message = greeting.concat(", ", name, "!");
console.log(message); // "Привет, Мир!"
```

### includes(substring): проверяет, содержится ли подстрока в строке, возвращая true или false
```Javascript
let text = "Я люблю JavaScript";
console.log(text.includes("люблю")); // true
```

### indexOf(substring): возвращает индекс первого вхождения подстроки или -1, если подстрока не найдена.
```Javascript
let text = "Я люблю JavaScript";
console.log(text.indexOf("люблю")); // 2
```

### replace(searchValue, newValue): заменяет первое вхождение подстроки на новую строку.
```Javascript
let text = "Я люблю JavaScript";
let newText = text.replace("люблю", "обожаю");
console.log(newText); // "Я обожаю JavaScript"
```

### slice(start, end): извлекает часть строки от start до end (не включая end).
```Javascript
let text = "Привет, мир!";
let substring = text.slice(0, 6);
console.log(substring); // "Привет"
```

### split(separator): разбивает строку на массив подстрок, используя разделитель.
```Javascript
let text = "яблоко,банан,вишня";
let fruits = text.split(",");
console.log(fruits); // ["яблоко", "банан", "вишня"]
```
