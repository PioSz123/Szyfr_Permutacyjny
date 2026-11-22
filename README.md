# Szyfr_Permutacyjny
Prosta aplikacja webowa do szyfrowania i deszyfrowania tekstu przez przestawianie znaków. Interfejs i algorytm są w jednym pliku [`index.html`](index.html), napisanym w HTML, CSS i JavaScript.
Uruchomienie
1. Pobierz index.html i otwórz go w przeglądarce. Aplikacja działa offline.
2. Wybierz Szyfrowanie lub Deszyfrowanie, wklej tekst i kliknij przycisk wybranej operacji.
3. W obu trybach wpisz co najmniej 8 znaków, w tym przynajmniej jeden znak inny niż biały.
Jak działa szyfr?
Aplikacja dzieli tekst na bloki po 6 znaków i odczytuje każdy blok w kolejności pozycji 3, 6, 1, 5, 2, 4. Permutacja jest wpisana na stałe. W krótszym ostatnim bloku aplikacja pomija brakujące pozycje. Podczas deszyfrowania znaki wracają na pierwotne miejsca.

Przykład: ABCDEFGH → CFAEBDGH → ABCDEFGH.
Numer indeksu 166202
