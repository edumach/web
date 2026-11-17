
# Jaké existují HTML značky?

Doposud jsme použili několik různých HTML značek:

```html
<h1>
<p>
<a>
<img>
<ul>
<li>
<table>
```

HTML obsahuje 124 značek.

Přestože mají různé účely, každá HTML značka patří vždy do dvou skupin:

1. bloková nebo řádková,
2. párová nebo nepárová.

---

## Blokové značky

Blokový prvek začíná na novém řádku a zabírá celou dostupnou šířku.

Příklady:

```html
<h1>
<p>
<ul>
<section>
<header>
<footer>
```

Příklad:

```html
<h1>Panská Open Air</h1>

<p>
Festival zaměřený na hudbu a technologie.
</p>
```

Výsledek:

```text
Panská Open Air

Festival zaměřený na hudbu a technologie.
```

Každý prvek začíná na novém řádku.


## Řádkové značky

Řádkové značky se zobrazují uvnitř textu.

Nezačínají na novém řádku.

Příklady:

```html
<a>
<strong>
<em>
```

Příklad:

```html
<p>
Navštivte
<a href="program.html">program festivalu</a>.
</p>
```

Výsledek:

```text
Navštivte program festivalu.
```

Odkaz zůstává součástí řádku.

---

## Párové značky

Párový prvek má:

- otevírací značku,
- uzavírací značku.

Příklad:

```html
<p>
Text odstavce.
</p>
```

Další příklady:

```html
<h1></h1>
<a></a>
<li></li>
<section></section>
```

Párové značky obvykle obsahují další obsah.


## Nepárové značky

Nepárový prvek nemá uzavírací značku.

Příklad:

```html
<img src="festival.jpg" alt="Festival">
```

Další příklady:

```html
<br>
<hr>
<meta>
```

Tyto značky většinou pouze něco vkládají nebo nastavují.

**Poznámka:** Můžeš se setkat i s takovým zápisem nepárové značky:

```html
<br />
<hr />
<img />
```

Je to pozůstatek dřívějších pravidel zápisu HTML. Prohlížeč i tomuto zápisu rozumí. I samotné uzavírací značky `</h1>`, `</p>`, `</li>`... vznikly až později. Měj na paměti, že jazyk HTML se vyvíjí přes 30 let. Za tu dobu vzniklo několik standardů.

---

## Přehled dosud známých značek

| Prvek | Blokový / řádkový | Párový / nepárový |
|---------|---------|---------|
| `<h1>` | blokový | párový |
| `<p>` | blokový | párový |
| `<a>` | řádkový | párový |
| `<strong>` | řádkový | párový |
| `<em>` | řádkový | párový |
| `<ul>` | blokový | párový |
| `<li>` | blokový | párový |
| `<table>` | blokový | párový |
| `<img>` | řádkový | nepárový |
| `<br>` | řádkový | nepárový |
| `<hr>` | blokový | nepárový |


## Zapamatuj si

HTML značky můžeme rozdělit podle dvou vlastností:

- jak se zobrazují (blokové × řádkové),
- zda mají uzavírací značku (párové × nepárové).

Toto rozdělení nám pomůže pochopit CSS a rozvržení stránky v dalších lekcích.


