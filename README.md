# Koszulka Fachowca · branding

Strona projektu nowego logo Koszulki Fachowca: logo, sygnet, kolory, nośniki marki i przykładowe posty.
Na końcu strony jest księga znaku w PDF do pobrania.

## Dwie wersje logo

Klient wybiera między dwiema opcjami kasku. Strona pokazuje obie w tej samej formie. Przełącznik „Wersja 1 / Wersja 2”
jest przypięty u góry i podmienia logo, zdjęcia, posty oraz księgę znaku, a pozycja przewijania zostaje.
Adres z `?wersja=2` otwiera stronę od razu na wersji 2.

## Podgląd lokalny

Strona jest statycznym plikiem HTML bez kroku budowania:

```bash
python3 -m http.server 8000
```

Potem `http://localhost:8000/`.

## Struktura

- `index.html` strona z obiema wersjami (style i skrypty w pliku, animacje wyłączone przy `prefers-reduced-motion`)
- `obrazy/` zdjęcia i plansze wersji 1 w WebP
- `obrazy-2/` to samo dla wersji 2
- `fonty/` Montserrat
- `pliki/` księga znaku w PDF, osobny plik dla każdej wersji

## Uwagi

- Zdjęcia nośników są wizualizacjami. Logo na nich pochodzi z plików pakietu marki.
- Strona ma `noindex`, bo służy do prezentacji projektu, nie do wyszukiwarki.
