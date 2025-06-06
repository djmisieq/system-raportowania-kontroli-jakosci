# System Raportowania - Dział Kontroli Jakości

## Opis projektu

System do zarządzania i raportowania pracy działu kontroli jakości. Umożliwia śledzenie godzin pracy, nadgodzin, kosztów oraz alokacji pracowników na różne linie produkcyjne i projekty.

## Funkcjonalności

### 📊 Dashboard
- Przegląd tygodniowy z kluczowymi metrykami
- Wykorzystanie zasobów w czasie rzeczywistym
- Analiza godzin przepracowanych vs dostępnych
- TOP 5 pracowników według przepracowanych godzin
- Podział godzin według linii produkcyjnych

### 📅 Alokacja Tygodniowa
- Planowanie przydziału pracowników na każdy dzień tygodnia
- Przypisywanie do linii produkcyjnych lub projektów
- Obsługa różnych statusów (Urlop, L4, Szkolenie)
- Zapisywanie i wczytywanie planów tygodniowych

### ⏱️ Raport Godzin
- Wprowadzanie rzeczywistych godzin przepracowanych
- Podział na linie produkcyjne i projekty
- Automatyczne obliczanie sum
- Porównanie z planem alokacji

### 👥 Dane HR
- Zarządzanie listą pracowników
- Ustalanie wymiaru etatu (FTE)
- Określanie dostępnych godzin tygodniowo
- Śledzenie statusu pracowników

### ⚙️ Ustawienia
- Export/Import danych
- Zarządzanie konfiguracją systemu
- Konfiguracja linii produkcyjnych i projektów

## Technologie

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Składowanie danych**: LocalStorage
- **Responsywność**: CSS Grid, Flexbox oraz media queries dla urządzeń mobilnych
- **UI/UX**: Nowoczesny design z gradientami i animacjami

## Instalacja i uruchomienie

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/djmisieq/system-raportowania-kontroli-jakosci.git
   ```

2. Otwórz plik `index.html` w przeglądarce internetowej

3. System jest gotowy do użycia!

## Korzystanie z systemu

### Pierwsze uruchomienie
1. Przejdź do zakładki "Dane HR" i sprawdź listę pracowników
2. Dostosuj wymiary etatów według potrzeb
3. Przejdź do "Alokacja Tygodniowa" i zaplanuj przydział na bieżący tydzień
4. Wprowadź rzeczywiste godziny w zakładce "Raport Godzin"
5. Sprawdź metryki w Dashboard

### Struktura danych
System operuje na następujących obszarach:
- **Linie produkcyjne**: Linia 1, Linia 2, Linia 3, Linia 4
- **Projekty**: Projekt A, Projekt B, Inne
- **Statusy**: Aktywny, Urlop, L4, Szkolenie

### Backup i przywracanie
- Użyj funkcji "Eksportuj dane" w Ustawieniach aby utworzyć kopię zapasową
- Dane można przywrócić używając "Importuj dane"

## Funkcje zaawansowane

- **Automatyczne obliczenia**: System automatycznie kalkuluje wykorzystanie zasobów
- **Wizualizacje**: Paski postępu pokazują wykorzystanie w czasie rzeczywistym
- **Responsywność**: Działa na urządzeniach mobilnych (≤600px) i desktop
- **Persystencja**: Dane są automatycznie zapisywane w przeglądarce

## Rozwój projektu

Planowane usprawnienia:
- [ ] Integration z bazą danych
- [ ] Eksport do Excel/PDF
- [ ] Zaawansowane raporty
- [ ] Powiadomienia o przekroczeniach
- [ ] API dla integracji z innymi systemami

## Wsparcie

W przypadku problemów lub pytań, utwórz issue w tym repozytorium.

## Licencja

Ten projekt jest dostępny na licencji MIT.
