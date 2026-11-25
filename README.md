# Koszulka Fachowca · branding

Strona projektu nowego logo Koszulki Fachowca: logo, sygnet, kolory, nośniki marki i przykładowe posty.
Na końcu strony jest księga znaku w PDF do pobrania.

## Podgląd lokalny

Strona jest statycznym plikiem HTML bez kroku budowania:

```bash
python3 -m http.server 8000
```

Potem `http://localhost:8000/`.

## Struktura

- `index.html` strona (style i skrypty w pliku, animacje wyłączone przy `prefers-reduced-motion`)
- `obrazy/` zdjęcia i plansze w WebP
- `fonty/` Montserrat
- `pliki/` księga znaku w PDF

## Uwagi

- Zdjęcia nośników są wizualizacjami. Logo na nich pochodzi z plików pakietu marki.
- Strona ma `noindex`, bo służy do prezentacji projektu, nie do wyszukiwarki.
