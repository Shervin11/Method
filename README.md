# Методы работы со строками в JavaScript

---

## _Основные методы_

### 1️⃣ _charAt_: возвращает символ по указанному индексу.
```Javascript
let text = "Привет, мир!";
console.log(text.charAt(0)); // "П"
```


### 2️⃣ _concat_: объединяет две или более строк и возвращает новую строку.
```Javascript
let greeting = "Привет";
let name = "Мир";
let message = greeting.concat(", ", name, "!");
console.log(message); // "Привет, Мир!"
```


### 3️⃣ _includes_: проверяет, содержится ли подстрока в строке, возвращая true или false
```Javascript
let text = "Я люблю JavaScript";
console.log(text.includes("люблю")); // true
```


###  4️⃣ _indexOf_: возвращает индекс первого вхождения подстроки или -1, если подстрока не найдена.
```Javascript
let text = "Я люблю JavaScript";
console.log(text.indexOf("люблю")); // 2
```


###  5️⃣ _replace_: заменяет первое вхождение подстроки на новую строку.
```Javascript
let text = "Я люблю JavaScript";
let newText = text.replace("люблю", "обожаю");
console.log(newText); // "Я обожаю JavaScript"
```

![scale_1200](https://github.com/user-attachments/assets/27f9a052-163c-4912-ba85-38b6abcffc2a)


###  6️⃣ _slice_: извлекает часть строки от start до end (не включая end).
```Javascript
let text = "Привет, мир!";
let substring = text.slice(0, 6);
console.log(substring); // "Привет"
```


###  7️⃣ _split_: разбивает строку на массив подстрок, используя разделитель.
```Javascript
let text = "яблоко,банан,вишня";
let fruits = text.split(",");
console.log(fruits); // ["яблоко", "банан", "вишня"]
```

###  8️⃣ _toLowerCase()_: преобразует все символы строки в нижний регистр.
```Javascript
let text = "ПрИвЕт, МиР!";
let lowerText = text.toLowerCase();
console.log(lowerText); // "привет, мир!"
```

###  9️⃣ _toUpperCase()_: преобразует все символы строки в верхний регистр.
```Javascript
let text = "ПрИвЕт, МиР!";
let upperText = text.toUpperCase();
console.log(upperText); // "ПРИВЕТ, МИР!"
```

###  🔟 _trim()_: удаляет пробелы с начала и конца строки.
```Javascript
let text = "  Привет, мир!  ";
let trimmedText = text.trim();
console.log(trimmedText); // "Привет, мир!"
```

## Number Method in JavaScript.
<details>
    <summary>Math.floor( )</summary>
<br>

***The Math.floor() function rounds down a number to the next smallest integer.***
<br>
<br>


let number = 43.6
console.log(Math.floor(number)); // 43

<br>
</details>

<details>
<summary>Math.ceil( )</summary>
<br>

***Math.ceil() method rounds a decimal number up to the next largest integer and returns it.***

<br>
<br>


let number = 43.6
console.log(Math.ceil(number)) // 44

<br>
</details>

<details>
    <summary>Math.round( )</summary>
<br>

***The Math.round() function returns the number rounded to the nearest integer.*** 
<br>


let number = 43.6
console.log(Math.round(number)) // 44

 <br>

</details>

<details>
    <summary>Math.abs( )</summary>
<br>

***abs() method finds the absolute value of the specified number (without any sign) and returns it.***
<br>


let number = -16
console.log(Math.abs(number)) // 16

<br>

</details>

<details>
    <summary>Math.max( )</summary>
<br>

***max() method finds the maximum value among the specified values and returns it.***
<br>


let number = 1784329
console.log(Matn.max(number)) // 9

<br>

</details>

<details>
    <summary>Math.min( )</summary>
<br>

***min() method finds the minimum value among the specified values and returns it.***
<br>


let number = 79871208
console.log(Math.min(number)) // 1

<br>

</details>

<details>
    <summary>Math.pow( )</summary>
<br>

***pow() method computes the power of a number by raising the second argument to the power of the first argument.***
<br>


let num1 = 2
let num2 = 3
console.log(Math.pow(num1 , num2)) // 8

<br>

</details>

<details>
    <summary>Math.sqrt( )</summary>
<br>

***sqrt() method computes the square root of a specified number and returns it***
<br>


let number = 16
console.log(Math.sqrt(number)) // 4

<br>

</details>

<details>
    <summary>Math.random( )</summary>
<br>

***random() function returns a floating-point, pseudo-random number between 0 (inclusive) and 1(exclusive).***
<br>


let numbers = Math.random( ) * 10
console.log(numbers) // 3.3334545

</details>

<details>
    <summary>isNaN( )</summary>
<br>

***isNaN() function checks if a value is NaN (Not-a-Number) or not***
<br>


console.log(isNaN( ) == 9999) // false
console.log(isNaN( ) == "9999" ) // true

</details>
