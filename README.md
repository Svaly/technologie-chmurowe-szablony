# Technologie chmurowe – szablony

Szablony do laboratorium z przedmiotu **Technologie chmurowe** (Uniwersytet Ekonomiczny w Katowicach, kierunek Gospodarka cyfrowa).

## Wizytówka z blogiem

Folder [`wizytowka`](wizytowka) zawiera gotową stronę w jednym pliku `index.html`: sekcje **O mnie**, **Projekty** i **Blog**.

Możesz z niej skorzystać zamiast generować stronę z AI albo potraktować ją jako punkt wyjścia i poprosić AI o zmianę wyglądu.

### Jak użyć

1. Pobierz plik `wizytowka/index.html` (przycisk **Download raw file** na GitHubie) i zapisz go w folderze `wizytowka` na swoim komputerze.
2. Otwórz plik w Notatniku i zmień teksty w sekcjach **O mnie** i **Projekty** na swoje.
3. Wpisy na blogu dodajesz w tablicy `posts` na dole pliku. Instrukcja jest w komentarzu nad tablicą.
4. Zrzut ekranu do wpisu zapisz w tym samym folderze (np. `zajecia1.png`) i wpisz jego nazwę w polu `obraz`.
5. Sprawdź stronę lokalnie (dwuklik na `index.html`), a potem wgraj **cały folder** na Cloudflare Pages według instrukcji z Classroom.

### Prywatność

W sekcji `<head>` jest linia `<meta name="robots" content="noindex">`. Dzięki niej Google nie pokaże Twojej strony w wynikach wyszukiwania. Jeśli chcesz, żeby strona była widoczna w Google, usuń tę linię.

Możesz też użyć pseudonimu zamiast imienia i nazwiska.
