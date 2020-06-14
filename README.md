# JavaScript Best Practice Guide
---

__1. Используйте camelCase для названий переменных, объектов и функций.__

```
const sayHelloToWorld = 'Hello, world!';
```

__2. Используйте const и let для объявления переменных.__

```
const x = false;
let y = 2;
```

__3. Не используй new Function для создания функций.__

```
const sayHello = function (name){
  console.log(`Hello ${name}!`);
};
```

__4. Всегда ставьте точку с запятой в конце выражения.__

```
const sayHello = function (name){
  console.log(`Hello ${name}!`);
};
```

__4. При использовании конструкции if .. else располагайте else на одной строке со скобкой закрывающей блок if.__

```
if (test) {
  thing1();
  thing2();
} else {
  thing3();
}
```

__5. Не оставляй пустые блоки в рабочем коде .__

```
try {
    doSomething();
} catch (ex) {
    // continue regardless of error
}
```

__6. Для объявления объекта использую фигурные скобки.__

```
const newObj = {};
```

__7. Используй квадратные скобки [ ] для объявления массивов.__

```
const newArr = [];
```

__8. Используй одинарные кавычки ' ' для строк.

```
const newStr = 'Hello!';
```

__9. Если в строке ты обращаешься к какой-либо переменной через ${variable} , то такая строка должна быть обернута в обратные кавычки.__

```
const sayHello = function (name){
  console.log(`Hello ${name}!`);
};
```

__10. Используй понятные выражения для названий переменных, объектов и функций.__

```
const getDate = new Date();
```
