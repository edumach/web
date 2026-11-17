
# Responzivní web

> Stejný dokument pro různá zařízení

## Co se naučíš

- přizpůsobit web různým zařízením
- používat media query

⚠️ **Podpora zobrazení na mobilních zařízeních:** Tento řádek je potřeba téměř na každé moderní webové stránce, aby správně fungovala na mobilních zařízeních.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Určuje, jak má prohlížeč zobrazit stránku na mobilních zařízeních. Zajistí, že stránka využije skutečnou šířku displeje a bude se správně přizpůsobovat různým velikostem obrazovek. Bez tohoto nastavení nemusí responzivní web na mobilu fungovat správně.


## Cvičný projekt

Přidej:

```css
@media (max-width: 800px) {
    main {
        grid-template-columns: 1fr;
    }
}
```

❓ Zkus odhadnout, jak kód funguje.


Vyzkoušej:

- zmenšování okna prohlížeče,
- simulaci mobilního telefonu v DevTools (Nástroje pro vývojáře).

## Rozšiřující úkol

Najdi další prvky, které by mohly vypadat jinak na mobilu.

## Na konci umím

- ✅ používat media query
- ✅ upravit web pro mobil
- ✅ vysvětlit princip responzivity
