# Zadania do Samodzielnego Wykonania

Poniżej znajduje się **5 zadań** do samodzielnego wykonania. Zadania są stopniowane pod względem trudności. Wykonuj je po kolei, każde kolejne zadanie bazuje na poprzednim. **Po ukończeniu każdego zadania utwórz commit i podaj jego nazwę**.

---

## Zadanie 1: Dodanie Nowej Kolumny do Tabeli

**Cel:** Rozszerzyć tabelę **`uczniowie`** o nową kolumnę **`klasa`**.

### Instrukcje:

- Dodaj do tabeli **`uczniowie`** nową kolumnę o nazwie **`klasa`** typu **VARCHAR** o długości **10**.
- Upewnij się, że nowa kolumna zostanie dodana do istniejących rekordów.
- Wprowadź odpowiednie wartości dla kolumny **`klasa`** dla każdego ucznia, np. **"1A"**, **"2B"**.
- **Utwórz commit i podaj jego nazwę:** `"Dodanie kolumny klasa do tabeli uczniowie"`

---

## Zadanie 2: Aktualizacja Skryptu PHP do Wyświetlania Nowej Kolumny

**Cel:** Zmodyfikować skrypt PHP, aby wyświetlał również nowo dodaną kolumnę **`klasa`**.

### Instrukcje:

- Edytuj plik **`index.php`**.
- Zaktualizuj zapytanie SQL, aby pobierało również kolumnę **`klasa`**.
- Dodaj odpowiednią kolumnę w tabeli HTML, aby wyświetlić wartość **`klasa`** dla każdego ucznia.
- **Utwórz commit i podaj jego nazwę:** `"Aktualizacja index.php do wyświetlania kolumny klasa"`

---

## Zadanie 3: Dodanie Formularza do Dodawania Nowych Uczniów

**Cel:** Utworzyć formularz, który pozwoli dodawać nowych uczniów do bazy danych poprzez stronę internetową.

### Instrukcje:

- Dodaj na stronie **`index.php`** formularz HTML z polami:
  - **Imię**
  - **Nazwisko**
  - **Wiek**
  - **Klasa**
- Utwórz nowy skrypt PHP lub rozszerz istniejący, aby po wysłaniu formularza dodał nowego ucznia do tabeli **`uczniowie`**.
- Upewnij się, że po dodaniu nowego ucznia, strona wyświetla zaktualizowaną listę uczniów.
- **Utwórz commit i podaj jego nazwę:** `"Dodanie formularza do dodawania uczniów"`

---

## Zadanie 4: Walidacja Danych w Formularzu

**Cel:** Zapewnić, że wszystkie pola w formularzu dodawania ucznia są wypełnione poprawnie.

### Instrukcje:

- Dodaj sprawdzanie po stronie serwera, aby upewnić się, że żadne pole nie jest puste.
- Jeśli któreś z pól jest puste, wyświetl odpowiedni komunikat błędu.
- Upewnij się, że **wiek** jest liczbą całkowitą większą od zera.
- Jeśli wszystkie dane są poprawne, dodaj ucznia do bazy danych.
- **Utwórz commit i podaj jego nazwę:** `"Dodanie walidacji danych w formularzu"`

---

## Zadanie 5: Usuwanie Uczniów z Bazy Danych

**Cel:** Dodać możliwość usuwania uczniów z bazy danych poprzez stronę internetową.

### Instrukcje:

- Przy każdym rekordzie ucznia w tabeli wyświetlanej na stronie dodaj przycisk lub link **"Usuń"**.
- Po kliknięciu w **"Usuń"**, uczeń powinien zostać usunięty z tabeli **`uczniowie`** w bazie danych.
- Po usunięciu ucznia, strona powinna wyświetlić zaktualizowaną listę uczniów.
- Upewnij się, że usuwanie jest wykonywane bezpiecznie i nie powoduje błędów.
- **Utwórz commit i podaj jego nazwę:** `"Dodanie funkcjonalności usuwania uczniów"`

---

**Powodzenia w wykonywaniu zadań! Pamiętaj o regularnym commitowaniu swoich postępów, aby śledzić zmiany i uniknąć utraty pracy.**
