# Språk

## HTML
### Hva er html?
* HyperText Markup Language
* Brukes for å strukturere innhold
* HTML er grunnmuren og veggene på en nettside.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First webpage</title>
</head>
<body>
    <div id="page">

        <article class="main">
            <h1>Hei! Velkommen til min side.</h1>

            <h2>Her kan du finne mye gøy om meg.</h2>

            <p>Jeg liker å lage mat og ta bilder.</p>

            <p>Liker også å drive med webutvikling.</p>
        </article>

    </div>
</body>
</html>
```

## CSS
### Hva er CSS?
* Cascading StyleSheet
* CSS er kun utsende

```css

body {
    background-color: pink;
}

#page {
    width: 600px;
    margin: 0 auto;
}

.main {
    font-family: Helvetica, Arial;
    color: yellow;
}

.main p {
    font-size: 12px;
    margin-bottom: 10px;
}

.main h1 {
    font-size: 24px;
    font-weight: bold;
}

.main h2 {
    font-size: 20px;
}

```

CSS kan legges inn som en ekstern .css fil:
```html
<link rel="stylesheet" href="filnavn.css">
```
eller du kan legge det inline:
```html
<style>
    .class {

    }
</style>
```


## JS
### Hva er JavaScript
* Funksjoner, Interaksjon med bruker.
* Elektronikk, Rør alt i bakgrunden du ikke ser.

Basic javascript kan se sånn ut:
```js

var a = 2;
var b = 10;

console.log(a + b); // 12
console.log(a * 2); // 4
console.log(a ^ 3); // 8
console.log(b / a); // 5
console.log(b - a); // 8
```

## lagring av data

### JSON - JavaScript Object Node: 
* mest brukt i API sammenheng, 
* JavaScript Syntax, 
        
### XML - Extensible Markup Language: 
* API
* litt utdatert, JSON har tatt over
* HTML syntax, 

### CSV - Comma Seperatet Values:
* mest brukt for store nedlastbare dataset, der bruker kanskje ikke har så mye erfaring med databehandling.
* kan åpnes i ExCel, 

### SQL - Structured Query Language:
* mest brukt i store datasystemer
* facebook, twitter, adressa, etc... 
