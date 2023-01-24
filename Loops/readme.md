### Table of Contents:

- [For Loops](#1-for-loops)
- [Do While Loops](#2-do-while-loops)
- [While Loops](#3-while-loops)
- [For...in Loops](#4-forin-loops)
- [For...of Loops](#5-forof-loops)

#### 1. For Loops

```javascript
for (let i = 0; i < 5; i++) {
    console.log(i)
}

// Output: 0 1 2 3 4
```

#### 2. Do While Loops

```javascript
let iterator = 0;

do {
    iterator++;
    console.log(iterator);
} while (iterator < 5)

// Output: 1 2 3 4 5
```

#### 3. While Loops

```javascript
let iterator = 0;

while (itearator < 5) {
    iterator++
    console.log(iterator)
}

// Output: 1 2 3 4 5
```

#### 4. For...in Loops

```javascript
const arr = [3, 5, 7]
arr. foo = 'hello'

for (let i in arr) {
    console.log(i)
}

// Output: "0", "1", "2", "foo"
```

#### 5. For...of Loops

```javascript
const arr = [3, 5, 7]
arr. foo = 'hello'

for (let i of arr) {
    console.log(i)
}

// Output: 3, 5, 7
```