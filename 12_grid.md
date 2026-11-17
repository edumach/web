
# Rozvržení stránky

> Grid je mřížka
> Grid pouze rozhoduje o rozmístění již existujících sekcí stránky. HTML určuje význam, CSS určuje rozložení.

## Co se naučíš

- používat CSS Grid
- vytvářet sloupce
- rozmisťovat obsah

🌐 Tutoriál: [https://www.w3schools.com/css/css_grid.asp](https://www.w3schools.com/css/css_grid.asp)

## Cvičný projekt

Vytvoř sekci:

```css
main {
    display: grid; /* Zapne Grid */
    grid-template-columns: 1fr 1fr; /* Vytvoří dva stejně široké sloupce */
    gap: 20px; /* Přidá mezeru mezi sloupci */
    padding: 20px;
}
```

> `fr` je zlomková jednotka. `1fr` se rovná 1 části dostupného prostoru.

- Do levého sloupce vlož informace o festivalu.
- Do pravého sloupce vlož program.

Stránka se nyní zobrazí přibližně takto:

```
+------------------+------------------+
| O festivalu      | Program          |
|                  |                  |
| text             | 12:00 DJ Nova    |
| text             | 14:00 ...        |
| text             | 18:00 ...        |
+------------------+------------------+
```

## Ukázkový příkad kódu

### HTML

```html
<body>

    <header>
        <h1>Panská Open Air 2027</h1>

        <p>
            Hudba, technologie, art...
        </p>
    </header>

    <nav>
        <a href="#">Domů</a>
        <a href="#">Program</a>
        <a href="#">Vstupenky</a>
        <a href="#">Kontakt</a>
    </nav>

    <main>

        <section>
            <h2>O festivalu</h2>

            <p>
                text...
            </p>

            <p>
                text...
            </p>
        </section>

        <section>
            <h2>Program</h2>

            <ul>
                <li>10:00 Zahájení</li>
                <li>...</li>
            </ul>
        </section>

    </main>

    <footer>
        <p>
            &copy; 2027 Panská Open Air
        </p>
    </footer>

</body>
</html>
```

### CSS

```css
main {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    padding: 20px;
}

section {
    border: 1px solid silver;
    padding: 15px;
}
```


## Rozšiřující úkol

Přidej třetí blok (`grid-template-columns: 1fr 1fr 1fr;`):

- mapa areálu,
- novinky,
- partneři.

## Na konci umím

- ✅ použít CSS Grid
- ✅ vytvořit vícesloupcové rozvržení
- ✅ rozdělit obsah do bloků
