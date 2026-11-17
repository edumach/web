
# HTTP server

> Klient–server v praxi

## Co se naučíš

- co je webový server
- proč používat localhost
- jak funguje komunikace klient-server

Do této chvíle:

```
file:///...
```

Od této chvíle:

```
http://localhost:8080
```


## Cvičný projekt

Spusť server: Ve složce s projektem klikni pravým tlačítkem myši a zvot Nový terminál. V něm zapiš příkaz:

```shell
python -m http.server 8080
```

Otevři v prohlížeči:

```text
http://localhost:8080
```

Vyzkoušej:

- otevření stránky,
- otevření obrázku,
- zadání neexistující adresy.

```text
prohlížeč
    ↓
HTTP request
    ↓
Python HTTP server
    ↓
HTTP response
    ↓
HTML
```



## Rozšiřující úkol

Zjisti význam kódů:

- 200
- 404
- 304

## Na konci umím

- ✅ spustit jednoduchý webový server
- ✅ otevřít projekt pomocí localhost
- ✅ vysvětlit princip klient-server

