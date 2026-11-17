
# DOM

## Co se naučíš

- co je DOM
- jak prohlížeč zpracovává HTML
- jak používat DevTools

DOM (**Document Object Model**) je způsob, jakým si prohlížeč představuje webovou stránku v paměti. Jednoduše:

> DOM je stromová reprezentace webové stránky, kterou si prohlížeč vytvoří z HTML a se kterou následně pracují CSS (i JavaScript).

HTML soubor je text. DOM je strom objektů, který z něj vytvoří prohlížeč.

Například z HTML:

```html
<body>
    <h1>Festival 2027</h1>
    <p>Vítejte na našem webu.</p>
</body>
```

vznikne zjednodušený DOM:

```
body
├── h1
│   └── Festival 2027
└── p
    └── Vítejte na našem webu.
```

**Každý prvek HTML se stane uzlem stromu.**

Jinými slovy: představ si web jako dům:

- **HTML** = stavební plán
- **DOM** = skutečný model domu **vytvořený prohlížečem**
- **CSS** = výmalba a vybavení
- JavaScript = možnost s DOMem za běhu manipulovat (otevřít dveře, rozsvítit světlo, přestavět pokoj)


## Cvičný projekt

Otevři stránku festivalu.

Pomocí **nástrojů pro vývojáře**:

- najdi element `<h1>`,
- změň jeho text,
- změň barvu,
- změň velikost písma.

Obnov stránku.

## Rozšiřující úkol

Vyhledej v DOM:

- navigaci,
- obrázky,
- tabulku,
- seznam programu,
- smaž např. u jednoho z nadpisů koncovou značku `</h1>` a zkontroluj DOM (prohlížeč si ji sám doplní). Např.:
    ```html
    <h1>Ahoj
    <p>Text</p>
    ```



## Na konci umím

- ✅ vysvětlit pojem DOM
- ✅ otevřít DevTools
- ✅ najít element na stránce

