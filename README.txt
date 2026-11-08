ETF PORTFOLIO MANAGER — KOMPLETNA PACZKA PWA

ZAWARTOŚĆ
- index.html: cała aplikacja (interfejs, kalkulator, import screenshotu/OCR, eksport CSV)
- manifest.webmanifest: konfiguracja instalacji jako aplikacja
- sw.js: cache offline i aktualizacja Service Workera (wersja v4)
- icon.svg: ikona aplikacji

WAŻNE
To jest aplikacja PWA, nie natywny plik APK. Nie łączy się z kontem XTB i nie wykonuje transakcji.
Wartości początkowe są przykładowe/historczne: VWCE 0 PLN, EMIM 237,04 PLN, gotówka 250,03 PLN.
Sprawdź i popraw dane przed użyciem.

JAK WGRAC CAŁĄ APLIKACJĘ OD NOWA NA GITHUB PAGES
1. Rozpakuj ZIP na komputerze.
2. Otwórz repozytorium GitHub, w którym publikujesz aplikację.
3. Usuń stare pliki aplikacji z głównego katalogu repozytorium (Root).
4. Wgraj bezpośrednio CZTERY pliki z tej paczki: index.html, manifest.webmanifest, sw.js, icon.svg oraz README.txt.
   Nie wgrywaj samego pliku ZIP i nie umieszczaj plików w dodatkowym podfolderze.
5. Zatwierdź zmiany przyciskiem Commit changes.
6. Sprawdź Settings > Pages: Source = Deploy from a branch, Branch = main, Folder = /(root).
7. Poczekaj na zakończenie publikacji GitHub Pages.
8. Na telefonie otwórz adres strony w Chrome. W menu Chrome wybierz „Zainstaluj aplikację” lub „Dodaj do ekranu głównego”.

ODŚWIEŻENIE STAREJ WERSJI NA ANDROIDZIE
- Zamknij aplikację.
- W Chrome otwórz adres witryny > informacje o stronie/Ustawienia witryny > Wyczyść dane.
- Otwórz ponownie stronę i zainstaluj aplikację ponownie, jeśli trzeba.
- Jeśli nadal widzisz starą wersję, odinstaluj skrót/PWA i dodaj ją ponownie.

FUNKCJE
- ręczna edycja wartości VWCE, EMIM i gotówki
- cel alokacji i kalkulator kolejnego zakupu
- symulacja długoterminowa
- eksperymentalny odczyt tekstu ze screenshotu przez Tesseract.js
- eksport CSV
- lokalny zapis danych i podstawowy tryb offline

OGRANICZENIA
- Ceny z Yahoo Finance mogą nie działać w przeglądarce z powodu CORS i mogą być opóźnione.
- OCR pokazuje odczytany tekst, nie aktualizuje automatycznie portfela. Przepisz/zweryfikuj wartości samodzielnie.
- Kalkulator nie uwzględnia prowizji, spreadów, podatków, minimalnych wartości zleceń ani ograniczeń zakupu ułamków ETF.
- Symulacja jest ilustracją matematyczną, nie prognozą ani poradą inwestycyjną.
