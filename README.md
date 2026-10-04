# Technologie chmurowe – szablony

Szablony do laboratorium z przedmiotu **Technologie chmurowe** (Uniwersytet Ekonomiczny w Katowicach, kierunek Gospodarka cyfrowa).

**Strona z szablonami: https://svaly.github.io/technologie-chmurowe-szablony/**

## Wizytówka z blogiem

Trzy szablony w jednym pliku `index.html`, każdy z sekcjami **O mnie**, **Projekty** i **Blog**. Działają tak samo, różnią się tylko wyglądem.

| Szablon | Folder | Wygląd |
|---|---|---|
| 1. Klasyczny | [`szablon-1/wizytowka`](szablon-1/wizytowka) | jasny, sam przechodzi w ciemny |
| 2. Ciemny | [`szablon-2/wizytowka`](szablon-2/wizytowka) | ciemny, blog jako oś czasu |
| 3. Z panelem bocznym | [`szablon-3/wizytowka`](szablon-3/wizytowka) | ciepłe kolory, menu po lewej |

### Jak użyć

1. Utwórz na pulpicie folder `wizytowka`.
2. Na stronie z szablonami wybierz szablon i kliknij **Pobierz index.html**. Zapisz plik w tym folderze.
3. Otwórz plik w Notatniku i zmień teksty w sekcjach **O mnie** i **Projekty** na swoje.
4. Wpisy na blogu dodajesz w tablicy `posts` na dole pliku. Instrukcja jest w komentarzu nad tablicą.
5. Zrzut ekranu do wpisu zapisz w tym samym folderze jako `zajecia1.png` (nazwa musi się zgadzać z polem `obraz`).
6. Sprawdź stronę lokalnie (dwuklik na `index.html`), a potem wgraj **cały folder** na Cloudflare (Workers & Pages → Create application → Upload your static files) według instrukcji z Classroom.
7. Każdy nowy wpis to nowa wersja strony: w Cloudflare wybierz **New deployment** i wgraj cały folder jeszcze raz.

### Prywatność

W sekcji `<head>` jest linia `<meta name="robots" content="noindex">`. Dzięki niej Google nie pokaże Twojej strony w wynikach wyszukiwania. Jeśli chcesz, żeby strona była widoczna w Google, usuń tę linię.

Możesz też użyć pseudonimu zamiast imienia i nazwiska.

## Struktura repozytorium

- `index.html` – strona główna z kafelkami szablonów (GitHub Pages)
- `szablon-N/index.html` – podstrona szablonu z podglądem i przyciskiem pobierania
- `szablon-N/wizytowka/` – sam szablon i przykładowy obrazek do wpisu
- `assets/` – arkusz stylów i miniatury
