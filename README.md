# Cal-Endure

Calendar and planning app for returned missionaries. It includes a dashboard, contacts, goals, and a calendar.

Built with Express, EJS, and Postgres.

Team: Noah Blake, Ethan Wood, Jacob Dishman, and George Summerill.

## Run locally

```bash
npm install
npm run dev
```

The server listens on `http://localhost:3000` unless `PORT` is set.

Postgres connection settings come from environment variables:

- `RDS_USERNAME` (default `postgres`)
- `RDS_HOSTNAME` (default `localhost`)
- `RDS_DB_NAME` (default `cal_endure`)
- `RDS_PASSWORD`
- `RDS_PORT` (default `5432`)
- `SESSION_SECRET`
