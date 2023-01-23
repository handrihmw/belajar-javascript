Dalam JavaScript, salah satu jenis ekspresi fungsi adalah arrow function.
Ini menampilkan sintaks yang lebih pendek tetapi mirip dengan fungsi konvensional.

Berikut adalah contoh fungsi reguler dan arrow function yang melakukan hal yang sama:

```javascript
// Regular Function
function add(a, b) {
    return a + b
}

// Arrow Function
const add = (a, b) => a + b
```

Saat berhadapan dengan fungsi tingkat tinggi, arrow function dapat membantu Anda menulis kode yang lebih ringkas _(fungsi yang menggunakan fungsi lain sebagai argumen)._

Anda dapat melihat cara menggabungkan fungsi standar dengan arrow function menggunakan metode map array dalam contoh ini:

```javascript
// Regular Function
const numbers = [1, 2, 3, 4, 5]
const double  = numbers.map(function(number) {
    return number * 2
})

// Arrow Function
const numbers = [1, 2, 3, 4, 5]
const double  = numbers.map(number => number * 2)
```

Fakta bahwa arrow function tidak memiliki nilai `this` sendiri adalah manfaat lain dari penggunaannya.
Cara pemanggilan fungsi menentukan nilai `this` dalam fungsi reguler.
Nilai `this` dalam arrow function diwariskan dari lingkup sekitarnya.
Dalam keadaan tertentu, ini dapat membuatnya lebih mudah untuk bekerja dengan `this`.

Berikut adalah beberapa contoh arrow function:

### Table of Contents:

- [Basic Arrow Function yang tidak menerima argumen apa pun dan memiliki block body.](#1-basic-arrow-function-yang-tidak-menerima-argumen-apa-pun-dan-memiliki-block-body)
- [Arrow Function yang tidak menerima argumen apa pun dan memiliki pengembalian implisit.](#2-arrow-function-yang-tidak-menerima-argumen-apa-pun-dan-memiliki-pengembalian-implisit)
- [Arrow function yang mengambil argumen tunggal dan memiliki badan blok dengan pengembalian eksplisit.](#3-arrow-function-yang-mengambil-argumen-tunggal-dan-memiliki-badan-blok-dengan-pengembalian-eksplisit)
- [Arrow Function bergaya blok multi-argumen dengan pengembalian eksplisit.](#4-arrow-function-bergaya-blok-multi-argumen-dengan-pengembalian-eksplisit)
- [Arrow Function dengan badan blok dan pernyataan log konsol tetapi tanpa argumen.](#5-arrow-function-dengan-badan-blok-dan-pernyataan-log-konsol-tetapi-tanpa-argumen)


#### 1. Basic Arrow Function yang tidak menerima argumen apa pun dan memiliki block body.

```javascript
// Basic Syntax
const func = () => {
    // function body
}
```

#### 2. Arrow Function yang tidak menerima argumen apa pun dan memiliki pengembalian implisit.

```javascript
// Implicit Return
const func = () => 'Hello World!'
```
#### 3. Arrow function yang mengambil argumen tunggal dan memiliki badan blok dengan pengembalian eksplisit.

```javascript
// Single Argument
const func = x => {
    return x * 2
}
```

#### 4. Arrow Function bergaya blok multi-argumen dengan pengembalian eksplisit.

```javascript
// Multiple Arguments
const func = (x, y) => {
    return x + y
}
```

#### 5. Arrow Function dengan badan blok dan pernyataan log konsol tetapi tanpa argumen.

```javascript
// No Arguments
const func = () => {
    console.log('Hello World!')
}
```

> References:
- [Source 1](https://twitter.com/csaba_kissi/status/1612086728151519232 "Source 1")