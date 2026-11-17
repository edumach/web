
# CSS a externí stylopis

> Jak má obsah vypadat

## Co se naučíš

- k čemu slouží CSS,
- jak vytvořit externí stylopis,
- jak propojit HTML a CSS,
- používat nejdůležitější CSS vlastnosti,
- vytvořit jednoduché efekty pomocí `:hover`.


## Co je CSS?

HTML popisuje obsah stránky. Například:

```html
<h1>Panská Open Air 2027</h1>

<p>Hudba, technologie a kreativita.</p>
```

HTML určuje:

- co je nadpis,
- co je odstavec,
- co je odkaz.

CSS určuje:

- barvy,
- písmo,
- velikosti,
- rozvržení.

Krátce:

> **HTML = obsah**
> **CSS = vzhled**

## Proč nepíšeme CSS do HTML?

Technicky bychom mohli psát styl přímo do HTML:

```html
<h1 style="color: red;">
    Panská Open Air
</h1>
```

Tento způsob má ale mnoho nevýhod:

- kód je nepřehledný,
- styl se obtížně mění,
- stejné nastavení musíme opakovat na více místech.

Proto se nejčastěji používá **externí stylopis**. 


## Vytvoření externího stylopisu

V projektu vytvoř soubor:

```text
panska-open-air/
│
├── index.html
└── style.css
```


## Propojení HTML a CSS

Do části `<head>` vlož:

```html
<link rel="stylesheet" href="style.css">
```

Například:

```html
<head>
    <meta charset="UTF-8">
    <title>Panská Open Air</title>

    <link rel="stylesheet" href="style.css">
</head>
```

Prohlížeč nyní při načtení stránky načte i soubor `style.css`.

---

## První CSS pravidlo

Soubor `style.css`:

```css
body {
    background-color: lightblue;
}
```

Výsledek:

- změní se pozadí stránky,
- HTML zůstane beze změny.


## Jak se zapisuje CSS?

Každé pravidlo má dvě části:

```css
selektor {
    vlastnost: hodnota;
}
```

Příklad:

```css
h1 {
    color: red;
}
```

- `h1` je selektor,
- `color` je vlastnost,
- `red` je hodnota.


## Nejdůležitější CSS vlastnosti

### Barva textu

```css
color: darkblue;
```

### Barva pozadí

```css
background-color: lightyellow;
```

### Písmo

```css
font-family: Arial, sans-serif;
```

### Velikost písma

```css
font-size: 20px;
```

### Šířka prvku

```css
width: 500px;
```

### Vnitřní odsazení

```css
padding: 20px;
```

# Praktický příklad

CSS:

```css
header {
    background-color: steelblue;
    color: white;

    padding: 20px;
}
```

Výsledek:

- modré pozadí,
- bílý text,
- odsazení obsahu.

---

## Pseudotřída `:hover`

Jedna z nejčastěji používaných vlastností na webu.

Pseudotřída `:hover` znamená:

> Když je kurzor myši nad prvkem.

### Základní příklad

```css
a:hover {
    color: red;
}
```

Po najetí myší na odkaz se změní barva textu.

### Praktický příklad

HTML:

```html
<nav>
    <a href="#">Domů</a>
    <a href="#">Program</a>
</nav>
```

CSS:

```css
nav a {
    color: navy;
}

nav a:hover {
    color: orange;
}
```

Po najetí myší odkaz změní barvu.


### Hezčí efekt

```css
nav a {
    color: black;
    padding: 5px 10px;
}

nav a:hover {
    background-color: steelblue;
    color: white;
}
```

Při přejetí myší se změní:

- pozadí,
- barva textu.

Stejný princip používá většina navigačních menu.

---

## Cvičný projekt

Vytvoř soubor:

```text
style.css
```

Připoj ho k projektu.


### Úkol 1

Nastyluj nadpis:

```css
h1 {
    color: darkblue;
}
```

### Úkol 2

Nastyluj hlavičku:

```css
header {
    background-color: steelblue;
    color: white;
    padding: 20px;
}
```

### Úkol 3

Přidej rámeček kolem sekcí:

```css
section {
    border: 1px solid silver;
    padding: 10px;
}
```

### Úkol 4

Přidej efekt při najetí myší:

```css
a:hover {
    color: orange;
}
```

## Na konci umím

- ✅ vytvořit externí stylopis
- ✅ propojit HTML a CSS
- ✅ používat selektory
- ✅ měnit barvy a písmo
- ✅ používat:
  - `color`
  - `background-color`
  - `font-family`
  - `font-size`
  - `width`
  - `padding`
  - `margin`
  - `border`
- ✅ používat pseudotřídu `:hover`
- ✅ vysvětlit rozdíl mezi HTML a CSS

## Zapamatuj si

- HTML odpovídá na otázku: **Co je to za obsah?**
- CSS odpovídá na otázku: **Jak má obsah vypadat?**

