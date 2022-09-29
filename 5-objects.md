# Objects

## Learn the Basics

* Understand why and how objects are used.

* Objects are also known as *dictionaries* in Python and *Hash Maps* in Java.

* We'll use JavaScript. But you should be able to follow along no matter which programming language you prefer.

**JavaScript**

* Do this chapter from Codecademy - https://www.codecademy.com/courses/introduction-to-javascript/lessons/objects/exercises/objects

* Read https://javascript.info/object - until “Copying by reference”

* Refer other resources if necessary.

**Python**

* Google for "dictionaries" and learn the basics

**Java**

* Google for "hash maps" and learn the basics

## Objects vs Arrays

[https://www.youtube.com/watch?v=iiV19OeSqmA](https://www.youtube.com/watch?v=iiV19OeSqmA)

## Why use Objects

[https://www.youtube.com/watch?v=EnBabBX6JPc](https://www.youtube.com/watch?v=EnBabBX6JPc)

## Case Study - Counting Uniques Problem

Code: [https://gitlab.com/snippets/1976631](https://gitlab.com/snippets/1976631)

[https://www.youtube.com/watch?v=FU4U1hSyZPk](https://www.youtube.com/watch?v=FU4U1hSyZPk)

## Case Study - Counting Pairs Problem

Code: [https://gitlab.com/snippets/1976634](https://gitlab.com/snippets/1976634)

[https://www.youtube.com/watch?v=jtSvUofvyRg](https://www.youtube.com/watch?v=jtSvUofvyRg)

## Exercises

### 1. Numbers and squares:

Define a function which returns an object containing the square of each number from 1 to n

```js
function squares(n) {
    // your code here.
}
```

Example: For n = 5. Your function should return:

```js
{
  "1": 1,
  "2": 4,
  "3": 9,
  "4": 16,
  "5": 25
}
```
_____________________

### 2. Countries and capitals

Consider the below string which contains countries and their capitals in csv format.

```js
`
"country","capital"
"Afghanistan","Kabul"
"Argentina","Buenos Aires"
"Australia","Canberra"
"Austria","Vienna"
"Bangladesh","Dhaka"
"Barbados","Bridgetown"
"Bhutan","Thimphu"
"Brazil","Brasília"
"Canada","Ottawa"
"China","Beijing"
"Denmark","Copenhagen"
"Egypt","Cairo"
"Finland","Helsinki"
"France","Paris"
"Germany","Berlin"
"Greece","Athens"
"India","New Delhi"
"Indonesia","Jakarta"
"Iran","Tehran"
"Iraq","Baghdad"
"Ireland","Dublin"
"Israel","Jerusalem"
"Italy","Rome"
"Japan","Tokyo"

`
```

Write a function that takes this string as an input argument and returns an object where the keys are the countires and the values are the corresponding capitals. Your output should look something like:

```js
{
  "Afghanistan": "Kabul",
  "Argentina": "Buenos Aires"
  etc...
}
```
