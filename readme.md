# Aplikacja Django + REST API (ćwiczenia)

Ćwiczenia z przedmiotu „Projektowanie aplikacji webowych”: aplikacja w Django z REST API (Django REST Framework) do zarządzania osobami, stanowiskami i zespołami.

*EN: Coursework: a Django app with a REST API (Django REST Framework) for managing people, job positions and teams.*

## Co jest w projekcie
- **Modele danych:** `Osoba`, `Stanowisko`, `Person`, `Team`, z relacjami i listami wyboru; 8 migracji.
- **REST API:** lista, szczegóły, dodawanie, edycja i usuwanie rekordów, wyszukiwanie osób po fragmencie imienia lub nazwiska, lista osób na danym stanowisku.
- **Uwierzytelnianie i uprawnienia:** tokeny, sesje i Basic Auth; część endpointów tylko dla zalogowanych.
- **Widoki HTML:** szablony z listą i szczegółami osób, własny CSS.
- **Rozwiązania zadań z laboratorium** (`lab3_zadanie_10.md`): zapytania w Django ORM.

## Technologie
Python, Django, Django REST Framework, SQLite.

## Uruchomienie
```
cd folder_projekt
pip install django djangorestframework
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## Autorka
Martyna Osial
