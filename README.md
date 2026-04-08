# GymHelper

Учебный full-stack проект для учета:
- недельного плана тренировок;
- выполненных тренировок по датам;
- питания по датам;
- сна и восстановления;
- статистики на дашборде;
- пользователей, ролей и сессионной авторизации.

Стек:
- `NestJS`
- `React`
- `PostgreSQL`
- `Prisma`
- `REST`
- `Swagger`
- `GraphQL`
- `SSE`

## Запуск

1. Установить зависимости:

```bash
npm install
```

2. Создать `.env` по примеру `.env.example`

3. Применить миграции и заполнить базу:

```bash
npm run prisma:migrate:deploy
npm run prisma:seed
```

4. Запустить проект:

```bash
npm run start:dev
```

## Основные команды

```bash
npm run build
npm run lint
npm run prisma:generate
npm run prisma:migrate:deploy
npm run prisma:seed
```

## Основные точки входа

- SPA: `/`
- Handlebars: `/lab1`, `/lab1/exercises`
- Swagger: `/api/docs`
- GraphQL: `/graphql`
