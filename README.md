# ReelInfo
<img src="fi.png" width="100" alt="ReelInfo Logo">


**ReelInfo** to nowoczesna, responsywna aplikacja internetowa, która pełni rolę informacyjnej bazy danych filmów i seriali. Projekt skierowany jest do miłośników kina, studentów, blogerów filmowych oraz wszystkich osób poszukujących aktualnych informacji o premierach, recenzjach i ciekawostkach filmowych.

## Funkcje aplikacji

- Przeglądanie listy premier filmów i seriali.
- Oglądanie zwiastunów bezpośrednio w aplikacji.
- Czytanie autorskich artykułów, recenzji i analiz filmowych.
- Korzystanie z formularza kontaktowego.
- Nawigacja po stronie za pomocą przejrzystej mapy strony.

## Technologie

- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
- **Backend:** Python, Flask
- **Baza danych:** MySQL
- **Inne narzędzia:** GitHub (kontrola wersji), Figma (projektowanie UI)

## Integracje

- API The Movie Database (TMDB) do dynamicznego pobierania danych o filmach i serialach.

## Wymagania systemowe

- Python 3.8+
- Flask
- MySQL Server
- Serwer VPS lub hosting z obsługą aplikacji Python
- Dostęp do internetu do komunikacji z API TMDB

## Instrukcja uruchomienia projektu lokalnie

1. Sklonuj repozytorium:
    ```bash
    git clone https://github.com/twoj-uzytkownik/reelinfo.git
    ```

2. Przejdź do katalogu projektu:
    ```bash
    cd reelinfo
    ```

3. Utwórz i aktywuj wirtualne środowisko:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate  # Windows
    ```

4. Zainstaluj wymagane pakiety:
    ```bash
    pip install -r requirements.txt
    ```

5. Skonfiguruj plik `.env` z kluczami API i danymi dostępowymi do bazy danych.

6. Uruchom aplikację:
    ```bash
    flask run
    ```

## Autorzy

- Michał Jacek Śmiałek — Programista Frontendowy
- Kamil Śnieżko — Programista Backendowy

## Licencja

Projekt ReelInfo jest udostępniony na licencji MIT.

---

> **Uwaga:** Projekt jest wciąż rozwijany — nowe funkcjonalności, takie jak rejestracja użytkowników, ocenianie filmów i komentowanie treści, są planowane w przyszłych aktualizacjach.
