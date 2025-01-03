# 6th semester; JavaScript, PHP, Laravel, Bootstrap, Tailwind notes:

_2 - jan - 2025_

JavaScript and PHP are scripting languages.

2 types of scripting languages:

- Server Side: stored and executed on server. Used to provide user interaction.
- Client Side: executed on client computers. Browsers support the use of these types of scripts. These could be embedded in HTML docs.

##### History of Javascript:

Created byu Brendan Eich in 1995 in the span of 10 days. It was first called Mocha, later they called it LiveScript but for trademark reasons they finally renamed it to its current name 'javascript'.

##### Javascript:

Javascript is an object oriented language and is light weighted and interpreted language. To define a variable you can use `var`, `const` or `let` keywords.
To use js inside html you need to use the `<script>` `</script>` tags. To write something in HTML you need to use `document.write()`.
Variables assigned using `const` cannot be replaced later in code.

##### Array:

3 ways to construct an array in js:

- By array literal: `var arr = [val, val2, val23]`
- By creating instance of array directly (using the `new` keyword): `var emp = new Array()`
- By using an array constructor (using the `new` keyword): `var emp = new Array("haroon", "azizi")`

**? js local vs. global variables?**
**? for/in vs. for/of**

_(end of lecture 1)_

---

A javascript object is a collection of named values which are referred to as properties. In this language almost everything is an object. Object is kinda similar to arrya, but in obj you define the keys yourself. To create an object we need to use `{}` curly braces:

```js
<scrpit>
    emp={
        id: 12,
        name: "haroon azizi"
        salary: 4000000230,
        onSite: true
    }
    document.write(emp.id+""+emp.name""+emp.salary)
</script>
```

You can create arrays of objects too. Meaning that you can have objects inside arrays.

```js
var objs = [
  { id: 12, name: "saghar" },
  { id: 23, name: "zulfeqar" },
];
```

##### Browser Object Model (BOM):

Is used to interact with the browser. The default object of the browser is the window, meaning that you can call it using funcitons of window. Most important and most used ones are `Alert()` and `confirm()`.

##### This 'History' Object:

It contains the browser session history, a list of all the visited pages in the current frame or window.

```js
history.back();
history.forward();
window.history.go(-2); // goes back two pages
window.history.go(1); // goes forward one page
```

_(end of lecture 2)_
