# API do Zarządzania Użytkownikami

Prosty backendowy system do zarządzania użytkownikami zbudowany przy użyciu FastAPI, SQLite i Dockera.

## Funkcje
- Tworzenie, listowanie i pobieranie użytkowników
- RESTful API
- Haszowanie haseł
- Obsługa przez Dockera

## Stos technologiczny
- Python 3.11
- FastAPI
- SQLite + SQLAlchemy
- Docker

## Jak zacząć

```bash
docker build -t user-api .
docker run -d -p 8000:8000 user-api
```

Dokumentacja API: http://localhost:8000/docs

## Zrzuty ekranu
![FastAPI Swagger UI](https://i.imgur.com/TwE4AgC.png)

## Do zrobienia
- [ ] Uwierzytelnianie JWT
- [ ] Aktualizacja/usuwanie użytkownika
- [ ] Testy jednostkowe przy użyciu Pytest
