# IO3A

# Projekt: Gry Hazardowe

## Opis projektu
Projekt zakłada stworzenie aplikacji do gier hazardowych. Aplikacja ma umożliwiać użytkownikom granie w ruletkę.

---

### Wymagania funkcjonalne
1. **Rejestracja użytkowników** – możliwość rejestracji i logowania się do aplikacji.
2. **Profil użytkownika** – przechowywanie i wyświetlanie informacji o użytkowniku, jego wynikach oraz historii gier.
3. **Obsługa gier** – implementacja kilku popularnych gier hazardowych (np. ruletka, poker, blackjack).
4. **System zakładów** – umożliwienie obstawiania i przyjmowania zakładów na wirtualne pieniądze.
5. **System rankingowy** – wyświetlanie rankingu graczy na podstawie ich wyników.
6. **Bezpieczne przetwarzanie danych** – zabezpieczenia przed oszustwami oraz bezpieczne przetwarzanie danych użytkowników.

---

### Wymagania niefunkcjonalne
1. **Wydajność** – czas odpowiedzi serwera na każde żądanie poniżej 2 sekund.
2. **Skalowalność** – możliwość obsługi wielu użytkowników jednocześnie, np. do 1000 aktywnych graczy.
3. **Bezpieczeństwo** – zabezpieczenie danych użytkowników oraz implementacja mechanizmów przeciwdziałania oszustwom.
4. **Dostępność** – aplikacja powinna być dostępna 24/7 z minimalnym czasem przestoju.
5. **Użyteczność** – prosty i intuicyjny interfejs dla użytkownika.
6. **Zgodność** – aplikacja powinna działać na różnych przeglądarkach (Chrome, Firefox, Safari).

---

### Potencjalne ryzyka
1. **Brak doświadczenia z bazami danych w C#** – zespół może mieć trudności z zaprojektowaniem i wdrożeniem odpowiedniej bazy danych.
2. **Niska znajomość ASP.NET** – konieczność szybkiego opanowania technologii ASP.NET do stworzenia interfejsu serwera i komunikacji z bazą danych.

---

### Lista ogólnych zadań do wykonania
1. **Przygotowanie środowiska projektowego** – konfiguracja repozytorium, wybór narzędzi i technologii.
2. **Projekt bazy danych** – zaprojektowanie struktury bazy danych dla użytkowników, gier i wyników.
3. **Frontend aplikacji** – stworzenie interfejsu użytkownika (UI) dla aplikacji.
4. **Backend aplikacji** – implementacja logiki serwera i obsługi gier przy użyciu ASP.NET.
5. **Bezpieczeństwo** – implementacja podstawowych zabezpieczeń dla danych użytkowników i transakcji.
6. **Testowanie** – testy jednostkowe i integracyjne aplikacji.
7. **Optymalizacja i skalowanie** – dopracowanie wydajności serwera, by radził sobie z większą liczbą użytkowników.

---

### Diagram aplikacji
Poniżej znajduje się prosty diagram architektury aplikacji, który przedstawia interakcję między użytkownikiem a serwerem aplikacji.

```plaintext
Użytkownik --> Strona internetowa --> Serwer aplikacji (ASP.NET) --> Baza danych

