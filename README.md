# Språk

## HTML
### Hva er html?
* HyperText Markup Language
* Brukes for å strukturere innhold
* HTML er grunnmuren og veggene på en nettside.

En HTML fil er bygged opp av tags, en tag har en start og en slutt
Her kan du se en paragraf tag, slutt taggen har nesten alltid / i slutt taggen.
```html
<p></p>
```
Det finnes unntag, som f.eks i en bilde tag som ikke har en slutt tag.
```html
<img src="dog.jpg" alt="bilde av en hund">
```

Du kan også se at en img tag har såklate *Attributes* dette er data verdier som er med på å bestemme hvordan tagggen skal oppføre seg.

**src** er image source, som da blir hvor du har bildet lagret.

**alt** er et alternativ til bildet om det ikke skulle vises, her er det best å beskrive bildet kort. Dette er for folk som har nettlesere som leser opp innholdet. pga forskjellige ting, kanskje de er blind.


Dette er en basic HTML side. 
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

En HTML5 fil starter alltid med *&lt;!DOCTYPE html&gt;* dette sier til nettleser at vi skal bruke verson 5 av html.
hele siden ligger så i en *&lt;html&gt;* tag.
etter html taggen har du 2 mulige tags, *&lt;head&gt;* og *&lt;body&gt;*, head er for det meste bare metadata for nettleser. selve siden ligger i *&lt;body&gt;*, her kan du begynne med p tagger og alt annet.


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
