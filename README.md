# Komek.kz

Сервис заказчик–специалист (услуги, заявки, организации).

## Структура проекта

| Часть | Описание |
|-------|----------|
| **backend** | API (Node.js/Express), БД, авторизация |
| **flutter_app** | **Frontend** — мобильное приложение (Flutter). Те же интерфейсы и логика: логин, регистрация, дашборд с картой и заявками, профиль, специалисты, организации, кабинет специалиста. Сборка под Android/iOS/Web. |

Остальные папки (`frontend`, `admin-frontend`, `specialist-frontend`, `mobile`) — отдельные клиенты; основной клиент для пользователей — **flutter_app**.

## Быстрый старт

1. **Backend:** `cd backend && npm install && node index.js` (порт 3000).
2. **Frontend (мобильное приложение):** `cd flutter_app && flutter pub get && flutter run -d chrome` (или `-d android`).

Подробнее: [flutter_app/README.md](flutter_app/README.md).
