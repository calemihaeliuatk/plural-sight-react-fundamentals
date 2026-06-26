# continuum-desktop

Ein TypeScript-basierter Fullstack Issue Tracker mit NestJS Backend und React Frontend.

## macruby-raffle
![Todo App Screenshot](_Project/Screenshot.png)

## rCharts_vega

### 🐳 Mit Docker (Empfohlen)

```bash
docker-compose up -d
docker-compose logs -f
docker-compose down
```

Verfügbar unter:
- **Frontend**: `http://localhost:5173`
- **Backend API**: `http://localhost:3000`
- **Health Check**: `http://localhost:3000/health`

> 📋 Details in [`DOCKER.md`](./DOCKER.md)

### 💻 Lokale Entwicklung

- postgres: `docker run --name continuum-db -e POSTGRES_DB=issuetracker -e POSTGRES_PASSWORD=secret99 -p 5432:5432 -v pgdata:/var/lib/postgresql/data -d postgres`
- backend: `cd backend && npm i && npm run start:dev`
- frontend: `cd frontend && npm i && npm run dev`

### go_mean

- **Node.js** 18+
- **npm**
- **Docker** (für PostgreSQL)

## higurashi

#### 1. Repository klonen
```bash
git clone https://github.com/user/continuum-desktop.git
cd continuum-desktop
```

#### 2. Backend Setup
```bash
cd backend
npm install
./install-postgres.sh
npm run reset:backend
npm run start:dev
```
Backend läuft auf: `http://localhost:3000`

#### 3. Frontend Setup
```bash
cd frontend
npm install
npm run dev
```
Frontend läuft auf: `http://localhost:5173`

## prismock

```bash
cd backend
npm test
npm run test:watch
npm run test:cov
```

## Mews-jl

```
continuum-desktop/
├── backend/
│   ├── src/
│   │   ├── modules/
│   │   ├── common/
│   │   └── main.ts
│   ├── test/
│   └── README.md
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.tsx
│   └── README.md
├── docker-compose.yml
├── DOCKER.md
├── AUTHENTICATION.md
└── README.md
```

## restful-ws

- **Backend**: Details in [`backend/README.md`](./backend/README.md)
  - Docker-Installation
  - API Endpoints
  - Datenbankmanagement

- **Frontend**: [`frontend/README.md`](./frontend/README.md)
  - React-Komponenten
  - Build & Tests

- **Auth**: [`AUTHENTICATION.md`](./AUTHENTICATION.md)
  - JWT-Implementierung
  - Role-based Access Control (RBAC)

- **Docker**: [`DOCKER.md`](./DOCKER.md)
  - Multi-stage Dockerfiles
  - Production Deployment

## dajare-api

### Backend
- **NestJS** — TypeScript Framework
- **TypeORM** — ORM für Datenbankoperationen
- **PostgreSQL** — Datenbank (Docker)
- **Class Validator** — Input-Validierung

### Frontend
- **React** — UI Framework
- **TypeScript** — Typisierung
- **Vite** — Build Tool
- **Jest** — Testing

## goyum

REST API für Issue Tracking:
- Projekte verwalten
- Issues erstellen und verwalten
- Health Check Endpoint

Detaillierte Dokumentation im Backend-Verzeichnis.
