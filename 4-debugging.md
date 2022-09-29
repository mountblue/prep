# Debugging

## Identify various kinds of errors + Case Study.

[https://www.youtube.com/watch?v=IVIlN22XDGQ](https://www.youtube.com/watch?v=IVIlN22XDGQ)

## Case Study Part 2 - How not to write code.

[https://www.youtube.com/watch?v=VHigeqECFVQ](https://www.youtube.com/watch?v=VHigeqECFVQ)

## Case Study Part 3 - Write better code.

[https://www.youtube.com/watch?v=W7awzvRbmqY](https://www.youtube.com/watch?v=W7awzvRbmqY)

## Learn to use debugging tools like PythonTutor

[https://www.youtube.com/watch?v=DL5TTbyo64o](https://www.youtube.com/watch?v=DL5TTbyo64o)

## Exercises

**1. Python Tutor**

Write a program to find the smallest value in an array.

Use [http://pythontutor.com/](http://pythontutor.com/) to visualize your code.

_____________

**2. Common Errors - Run the following code snippets and observe errors.**

 (If you are using a language other than JavaScript, try to recreate the same errors in your language)


`ReferenceError: variable is not defined`

```js
let arr = [1, 2, 3]
ar.push(4);
```
_______

`TypeError: Cannot read property 'x' of undefined`

```js
function doubleArrayElements(arr) {
    let b = [];
    for (let a of arr) {
        b.push(a * 2);
    }
    return b;
}
```

________

`Silent errors - mostly due to type coersion`

Adding string to number

```js
let x = 1;
let y = "2"
console.log(x + y);
```

Adding a number to an array

```js
let arr = [1, 2, 3, 4];
let y = 5
z = arr + y;
console.log(z)

```

Dividing by 0

```js
console.log(1 / 0);
```
Parse Int - NaN

```js
let word = "hello"
let number = parseInt(word);
function square(n) {
    return n * n;
}
console.log(square(number));
```
