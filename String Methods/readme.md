### Table of Contents:

- [length()](#1-length)
- [indexOf()](#2-indexof)
- [substring()](#3-substring)
- [replace()](#4-replace)
- [charAt()](#5-charat)
- [concat()](#6-concat)
- [includes()](#7-includes)
- [endsWith()](#8-endswith)

#### 1. length()
Metode `length()` mengembalikan panjang string

```javascript
let str = "Hello World";

console.log(str.length);

// Output: 11
```

#### 2. indexOf() 
Metode `indexOf()` mencari nilai tertentu dalam string dan mengembalikan posisi kecocokan.

```javascript
let str = "Hello World";

console.log(str.indexOf("World"));

// Output: 6
```

#### 3. substring()
Metode `substring()` mengekstrak karakter dari string antara dua indeks yang ditentukan, dan mengembalikan sub-string baru.

```javascript
let str = "Hello World";

console.log(str.substring(6, 11));

// Output: World
```

#### 4. replace()
Metode `replace()` mencari string untuk nilai tertentu dan menggantinya dengan nilai baru.

```javascript
let str = "Hello World";

console.log(str.replace("World", "there")); 

// Output: Hello there
```

#### 5. charAt()
Metode `charAt()` mengembalikan karakter pada indeks yang ditentukan dalam sebuah string.

```javascript
let str = 'Hello World';

console.log(str.charAt(0)) ;

// Output: H
```

#### 6. concat()
Metode `concat()` menggabungkan dua atau lebih string dan mengembalikan string baru.

```javascript
let str1 = 'Hello';
let str2 = 'World';

console.log(str1.concat(' ', str2));

// Output: Hello World
```

#### 7. includes()
Metode `include()` memeriksa apakah suatu string berisi string/karakter tertentu.

```javascript
let str = 'Hello World';

console.log(str.includes('World')) ;

// Output: true
```

#### 8. endsWith()
Metode `endsWith()` memeriksa apakah sebuah string diakhiri dengan karakter dari string yang ditentukan, mengembalikan benar atau salah.

```javascript
let str = 'Hello World';

console.log(str.endsWith('orld')); 

// Output: true
```

> References:
- [Source 1](https://twitter.com/csaba_kissi/status/1604130799661584386 "Source 1")