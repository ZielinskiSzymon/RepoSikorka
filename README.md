# Simple To-Do App

Prosta aplikacja webowa do zarządzania codziennymi zadaniami, umożliwiająca dodawanie, oznaczanie jako wykonane oraz usuwanie pozycji z listy.

---

## 🚀 Co zostało zrobione w projekcie?

W ramach projektu zrealizowano:

- **Architekturę CRUD:** pełna obsługa tworzenia (Create), odczytu (Read), aktualizacji statusu (Update) i usuwania (Delete) zadań.
- **Interfejs użytkownika (Frontend):** responsywny, minimalistyczny panel dostosowany do urządzeń mobilnych i desktopowych.
- **Zapis danych (Persistence):** przechowywanie wpisów w lokalnej bazie danych SQLite / pamięci podręcznej przeglądarki (`localStorage`), dzięki czemu stan nie resetuje się po odświeżeniu strony.
- **Walidację formularzy:** blokada dodawania pustych wpisów oraz zabezpieczenie przed duplikatami.
- **Filtrowanie i statusy:** możliwość wyświetlania zadań wg filtrów: *Wszystkie*, *Aktywne*, *Zakończone*.

---

## 🛠️ Technologie

- **Backend:** Python (Flask) / Node.js
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
- **Baza danych:** SQLite

---

## 📦 Wymagania wstępne

- Python w wersji `3.9+` (lub Node.js `18+` w zależności od wybranego stosu)
- Menedżer pakietów `pip` / `npm`
- Przeglądarka internetowa (Chrome, Firefox, Safari, Edge)

---

## ⚙️ Instalacja i uruchomienie

1. **Sklonuj repozytorium:**
   ```bash
   git clone [https://github.com/twoj-login/twoj-projekt.git](https://github.com/twoj-login/twoj-projekt.git)
   cd twoj-projekt