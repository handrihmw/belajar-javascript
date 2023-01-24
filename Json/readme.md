### JSON (JavaScript Object Notation)

JSON (JavaScript Object Notation) adalah format pertukaran data ringan yang mudah dibaca dan ditulis oleh manusia dan mudah diurai dan dibuat oleh mesin.

Ini didasarkan pada subset dari Bahasa Pemrograman JavaScript.

JSON adalah format teks yang sepenuhnya bebas bahasa tetapi menggunakan konvensi yang akrab bagi pemrogram dari keluarga bahasa C, termasuk C++, C#, Java, JavaScript, Perl, Python, dan banyak lainnya.

Properti ini menjadikan JSON sebagai bahasa pertukaran data yang ideal.

Di mana JSON digunakan?

JSON umumnya digunakan untuk mengirimkan data antara server dan aplikasi web atau antara dua aplikasi web.

Itu juga sering digunakan sebagai format penyimpanan data sederhana, baik sebagai file datar atau dalam database NoSQL seperti MongoDB atau CouchDB.

### Table of Contents:

- [JSON Object](#1-json-object)
- [JSON Parse](#2-json-parse)
- [JSON Stringify](#3-json-stringify)

#### 1. JSON Object
Contoh sederhana JSON object

```javascript
{
    "nama": "Budi",
    "umur": 27,
    "kota": "Yaogyakarta"
}
```

#### 2. JSON Parse
Di JavaScript, Kamu bisa menggunakan metode `JSON.parse()` untuk mengurai JSON string dan mengubahnya menjadi JavaScript object.

```javascript
const jsonString = '{"nama": "Budi", "umur": 27, "kota": "Yaogyakarta"}'
const orang = JSON.parse(jsonString)

console.log(orang.nama)

// output: Budi
```

#### 3. JSON Stringify
Kamu juga bisa menggunakan metode `JSON.stringify()` untuk mengonversi objek JavaScript menjadi JSON string.

```javascript
const orang = {
    "nama": "Budi",
    "umur": 27,
    "kota": "Yaogyakarta"
}

const jsonString = JSON.stringify(orang)

console.log(jsonString)

// output: {"nama": "Budi", "umur": 27, "kota": "Yaogyakarta"}
```

> References:
- [Source 1](https://twitter.com/csaba_kissi/status/1603756362168688640 "Source 1")