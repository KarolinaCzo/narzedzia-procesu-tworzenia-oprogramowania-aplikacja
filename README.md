# Spedycja

## Spis treści

- Podstawowe informacje
- Instrukcja
- Przydatne informacje

## Podstawowe informacje

### Nazwa

Spedycja

### Opis projektu

Aplikacja przygotowana została na potrzeby przedmiotu: Narzędzia procesu tworzenia oprogramowania (II semestr, Informatyka stosowana, Wyższa Szkoła Ekonomiczna w Białymstoku). 

Założeniem projektu było:
- zapoznanie się z językiem programowania PHP,
- nabycie umiejętności tworzenia baz danych oraz ich obsługi,
- skorzystanie z możliwości GIT-a w celu śledzenia zmian w projekcie.

### Opis zmian

W stosunku do projektu pierwotnego wprowadziłam następujące zmiany:
- stronę informującą o konieczności logowania (welcome.php),
- landing page z powitaniem i opisem aplikacji (landing.php),
- zmieniłam konstrukcję metod POST, gdyż wcześniejsze implementacje nie działały (zmiany nie były zapisywane w bazie),
- uwzględniłam możliwość dodawania kierowcy (carrier_add.php),
- dodałam Bootstrap'owe komponenty (alert) do wyświetlania informacji o poprawnym/niepoprawnym zapisie do bazy danych,
- dodałam stylowanie css do wielu komponentów, aby poprawnie dostosowywały się do ilości wyświetlanej treści.

## Instrukcja

Kroki, które należy podjąć aby odpalić projekt:
1. Zainstalować pakiet xampp.
2. Sklonować repozytorium do folderu htdocs.
3. Uruchomić xampp i odpalić moduł Apache i MySQL
4. Dodać bazę danych 'spedycja' do baz danych na serwerze (zrzut bazy danych znajduje się w repozytorium - spedycja.sql)
5. Uruchomić aplikację poprzez wejście na http://localhost/spedycja/
6. Korzystanie z aplikacji wymaga logowania: zarówno login i hasło pozostało niezmienione w stosunku do projektu pierwotnego.

## Przydatne informacje

Linki do zasobów, które zostały wykorzystane projekcie:
- Bootstrap
  https://getbootstrap.com/
- w trakcie pracy napotkałam problem związany z uprawnieniami do plików w folderze htdocs - Linux zezwalał na ich edycję tylko dla użytkownika root. W linku znajdują się przydatne wskazówki jak zmienić uprawnienia do plików:
  https://stackoverflow.com/questions/3740152/how-do-i-change-permissions-for-a-folder-and-all-of-its-subfolders-and-files-in
- dokumentacja PHP
  https://www.php.net/docs.php
- kurs bazy danych
  https://miroslawzelent.pl/kurs-mysql/
- kurs PHP
  https://miroslawzelent.pl/kurs-php/
