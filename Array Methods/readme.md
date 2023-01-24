### Table of Contents:

- [push()](#1-push)
- [pop()](#2-pop)
- [shift()](#3-shift)
- [unshift()](#4-unshift)
- [indexOf()](#5-indexof)
- [slice()](#6-slice)
- [splice()](#7-splice)
- [forEach()](#8-foreach)

#### 1. push()
Metode ini menambahkan satu atau lebih elemen ke akhir array dan mengembalikan panjang array yang baru.

```javascript
const cities = ['Jakarta', 'Semarang']

// tambahkan 'Yogyakarta' di akhir array
const newLength = cities.push('Yogyakarta')

console.log(cities)
// Output: ['Jakarta', 'Semarang', 'Yogyakarta']

console.log(newLength)
// Output: 3
```

#### 2. pop()
Metode ini menghapus elemen terakhir dari array dan mengembalikan elemen tersebut.

```javascript
const cities = ['Jakarta', 'Semarang', 'Yogyakarta']

// hapus elemen terakhir dari array
const last = cities.pop()

console.log(cities)
// Output: ['Jakarta', 'Semarang']

console.log(last)
// Output: Yogyakarta
```

#### 3. shift()
Metode ini menghapus elemen pertama dari array dan mengembalikan elemen tersebut.

```javascript
const cities = ['Jakarta', 'Semarang', 'Yogyakarta']

// hapus elemen pertama dari array
const first = cities.pop()

console.log(cities)
// Output: ['Semarang', 'Yogyakarta']

console.log(first)
// Output: Jakarta
```

#### 4. unshift()
Metode ini menambahkan satu atau lebih elemen ke awal array dan mengembalikan panjang array yang baru.

```javascript
const cities = ['Semarang', 'Yogyakarta']

// tambahkan 'Jakarta' ke awal array
const newLength = cities.unshift('Jakarta')

console.log(cities)
// Output: ['Jakarta', 'Semarang', 'Yogyakarta']

console.log(newLength)
// Output: 3
```

#### 5. indexOf()
Metode ini mencari array untuk item yang ditentukan dan mengembalikan posisinya.

```javascript
const cities = ['Jakarta', 'Semarang', 'Yogyakarta']

// cari index dari 'Semarang' didalam array
const index = cities.indexOf('Semarang')

console.log(cities)
// Output: ['Jakarta', 'Semarang', 'Yogyakarta']

console.log(index)
// Output: 1
```

#### 6. slice()
Metode ini mengembalikan salinan dangkal dari sebagian array ke dalam objek array baru.

```javascript
const cities = ['Jakarta', 'Semarang', 'Yogyakarta', 'Bandung', 'Surabaya']

// dapatkan sub-array dari elemen kedua dan ketiga
const subArray = cities.slice(1, 3)

console.log(cities)
// Output: ['Jakarta', 'Semarang', 'Yogyakarta', 'Bandung', 'Surabaya']

console.log(subArray)
// Output: [ 'Semarang', 'Yogyakarta' ]
```

#### 7. splice()
Metode ini menambah/menghapus elemen dari array dan mengembalikan item yang dihapus.

```javascript
const cities = ['Jakarta', 'Semarang', 'Yogyakarta', 'Bandung', 'Surabaya']

// hapus elemen kedua dan ketiga
const removed = cities.splice(1, 2)

console.log(cities)
// Output: [ 'Jakarta', 'Bandung', 'Surabaya' ]

console.log(removed)
// Output: [ 'Semarang', 'Yogyakarta' ]
```

#### 8. forEach()
Metode ini mengeksekusi fungsi yang disediakan satu kali untuk setiap elemen array.

```javascript
const cities = ['Jakarta', 'Semarang', 'Yogyakarta']

// cetak setiap elemen array
cities.forEach(city => {
    console.log(city)
})

// Output: Jakarta Semarang Yogyakarta
```

> References:
- [Source 1](https://twitter.com/csaba_kissi/status/1603388748485599234 "Source 1")