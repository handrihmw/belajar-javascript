### Tips & Trick

#### 1. Kamu dapat menggunakan operator `typeof` untuk memeriksa tipe nilai saat runtime.

```javascript
console.log(typeof 123) // "number"
console.log(typeof 'abc') // "string"
console.log(typeof true) // "boolean"
console.log(typeof {}) // "object"
console.log(typeof []) // "object"
console.log(typeof null) // "object"
console.log(typeof undefined) // "undefined"
```

#### 2. Operator `instanceof` dapat digunakan untuk menentukan apakah suatu objek merupakan turunan dari konstruktor atau kelas tertentu.

```javascript
class Orang {}
const orang = new Orang()

console.log(orang instanceof Orang) // true
console.log(orang instanceof Object) // true
```

#### 3. Operator `in` dapat digunakan untuk menentukan apakah suatu objek memiliki properti tertentu.

```javascript
const obj = { a: 1, b: 2, c: 3 }

console.log('a' in obj) // true
console.log('d' in obj) // false
```

#### 4. Kamu bisa mendapatkan larik properti enumerable object dengan menggunakan metode `Object.keys()`.

```javascript
const obj = { a: 1, b: 2, c: 3 }

console.log(Object.keys(obj)) // [ 'a', 'b', 'c' ]
```

#### 5. Metode `Object.entries()` mengembalikan larik pasangan nilai kunci properti yang dapat dihitung dari objek.

```javascript
const obj = { a: 1, b: 2, c: 3 }

console.log(Object.entries(obj)) // [ [ 'a', 1 ], [ 'b', 2 ], [ 'c', 3 ] ]
```

#### 6. Untuk memperoleh elemen pertama dalam larik yang memenuhi kriteria, gunakan metode `Array.prototype.find()`.

```javascript
const users = [
    { name: 'Alma', age: 25 },
    { name: 'Rina', age: 23 },
    { name: 'Ika', age: 20 },
]

const user = users.find(user => user.age >= 23)

console.log(user) // { name: 'Alma', age: 25 }
```

#### 7. Untuk menggabungkan banyak objek menjadi satu, gunakan metode `Object.assign()`.

```javascript
const defaultOptions = {
    width: 100,
    height: 100
}

const options = Object.assign({}, defaultOptions, {
    width: 200
})

console.log(options) // { width: 200, height: 100 }
```

#### 8. Gunakan operator `...` untuk menyebarkan array ke dalam argumen fungsi

```javascript
function sum(x, y, z) {
    return x + y + z
}

const numbers = [1, 2, 3]

console.log(sum(...numbers)) // 6
```

#### 9. Untuk mengulang string beberapa kali, gunakan metode `String.prototype.repeat()`.

```javascript
console.log('Ha'.repeat(3)) // HaHaHa
```

#### 10. Anda dapat menggunakan metode `Array.prototype.includes()` untuk memeriksa apakah suatu array menyertakan nilai tertentu.

```javascript
console.log([1, 2, 3].includes(2)) // true
```

> References:
- [Source 1](https://twitter.com/csaba_kissi/status/1612449120324567043 "Source 1")
- [Source 2](https://twitter.com/csaba_kissi/status/1611730636569559040 "Source 2")