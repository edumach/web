
# Odkazy a struktura webu

> Dokumenty se propojují
> Už nevytváříš jednu stránku, ale web

## Co se naučíš

- vytvářet více stránek
- propojovat stránky odkazy
- rozdělit obsah projektu

## Cvičný projekt

Ve složce projektu vytvoř:

```text
panska-open-air/
│
├── index.html
├── program.html
├── vstupenky.html
└── kontakt.html
```

V každém souboru vytvoř kostru HTML doumentu:

```html
<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <title></title>
</head>
<body>
    
</body>
</html>
```

Rozděl obsah:

| Soubor | Obsah (nadpis `<h1>`) | Text titulku | 
| --- | --- | --- |
| `index.html` | O festivalu | `Panská Open Air \| O festivalu` | 
| `program.html` | Program | `Panská Open Air \| Program` |
| `vstupenky.html` | Vstupenky | `Panská Open Air \| Vstupenky` |
| `kontakt.html` | Kontakt | `Panská Open Air \| Kontakt` |

Na každou stránku přidej navigaci:

```html
<nav>
    <a href="index.html">Domů</a>
    <a href="program.html">Program</a>
    <a href="vstupenky.html">Vstupenky</a>
    <a href="kontakt.html">Kontakt</a>
</nav>
```

## Rozšiřující úkol

Přidej odkaz na:

- web školy,
- oblíbeného interpreta,
- sociální síť festivalu (smyšlenou). Jako cíl odkazu stačí zapsat `#` (`href="#"`)

## Na konci umím

- ✅ vytvořit odkaz
- ✅ používat atribut `href`
- ✅ propojit více HTML souborů
- ✅ orientovat se ve struktuře projektu
