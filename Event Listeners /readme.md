### Table of Contents:

- [Menggunakan metode addEventListener](#1-menggunakan-metode-addeventlistener)
- [Menggunakan metode on](#2-menggunakan-metode-on)
- [Menggunakan metode on dengan delegation event](#3-menggunakan-metode-on-dengan-delegation-event)
- [Menggunakan metode addEventListener dengan delegation event](#4-menggunakan-metode-addeventlistener-dengan-delegation-event)
- [Menggunakan metode on dengan event handler sebaris](#5-menggunakan-metode-on-dengan-event-handler-sebaris)
- [Menggunakan metode addEventListener dengan fungsi anonim](#6-menggunakan-metode-addeventlistener-dengan-fungsi-anonim)
- [Menggunakan metode on dengan named functions:](#7-menggunakan-metode-on-dengan-named-functions-)
- [Menggunakan metode addEventListener dengan named functions](#8-menggunakan-metode-addeventlistener-dengan-named-functions)

#### 1. Menggunakan metode addEventListener

```javascript
let button = document.getElementById("myButton")

button.addEventListener("click", function() {
    console.log("Button was Clicked!")
})
```

#### 2. Menggunakan metode on

```javascript
let button = document.getElementById("myButton")

button.onclick = function() {
    console.log("Button was Clicked!")
}
```

#### 3. Menggunakan metode on dengan delegation event

```javascript
document.body.onclick = function(event) {
    if (event.taget.tagName === "BUTTON") {
        console.log("Button was Clicked!")
    }
}
```

#### 4. Menggunakan metode addEventListener dengan delegation event

```javascript
document.body.addEventListener("click", function(event) {
    if (event.taget.tagName === "BUTTON") {
        console.log("Button was Clicked!")
    }
})
```

#### 5. Menggunakan metode on dengan event handler sebaris

```javascript
<button onclick="console.log('Button was Clicked!')">Click Me</button>
```

#### 6. Menggunakan metode addEventListener dengan fungsi anonim

```javascript
let button = document.getElementById("myButton")

button.addEventListener("click", function() {
    console.log("Button was Clicked!")
})
```

#### 7. Menggunakan metode on dengan named functions:

```javascript
let button = document.getElementById("myButton")

function handleClick() {
    console.log("Button was Clicked!")
}

button.onclick = handleClick
```

#### 8. Menggunakan metode addEventListener dengan named functions

```javascript
let button = document.getElementById("myButton")

function handleClick() {
    console.log("Button was Clicked!")
}

button.addEventListener("click", handleClick)
```

> References:
- [Source 1](https://twitter.com/csaba_kissi/status/1610301467100954625 "Source 1")