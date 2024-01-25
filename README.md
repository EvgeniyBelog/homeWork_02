Задание 1 – Создать объект counter всеми возможными способами.
const counter = {a:1}
const counter1 = new Object()
const counter2 = Object.create(null)
const counter3 = Object.assing({}, counter)

Задание 2 – Скопировать объект counter всеми
возможными способами.
const copyCounter = Object.create(counter)
const copyCounter1 = Object.assing({}, counter)
const copyCounter2 = {...counter}
const copyCounter3 = JSON.parse(JSON.stringify(counter))
const copyCounter4 = structuredClone(counter)

Задание 3 – Создать функцию makeCounter всеми описанными и возможными способами.

function makeCounter(a, b){
 console.log (a + b)
}

const counter = function(a, b){
 console.log(a + b)
}

const counter2 = function makeCounter(a, b){
 console.log(a + b)
}

const counter3 = (a, b) => console.log(a + b)


Бонус
Задание 1 –
Написать функцию глубокого сравнения двух объектов:

const obj1 = { here: { is:
"on", other: "3" }, object: "Y" };

const obj2 = { here: { is:
"on", other: "2" }, object: "Y" };

const deepEqual =
(obj1, obj2) => {};

Бонус 
Задание 2 –
Развернуть строку в обратном направлении при помощи методов массивов:

function reverseStr(str) {
  return str.split('').reverse().join('')
}
