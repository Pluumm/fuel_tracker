
# 🧠 Backend (.NET 10)

## Run Backend
```bash
dotnet run --project backend/src/Api/Api.csproj
```

## Run Backend (Hot Reload)
```bash
dotnet watch run --project backend/src/Api/Api.csproj
```
## Build Solution
```bash
dotnet build backend/FuelTracker.sln
```
## Run Tests
```bash
dotnet test backend/FuelTracker.sln
```
## Database Migration (EF Core)
```bash
dotnet ef database update --project backend/src/Infrastructure
```
## ⚛️ Frontend (React + Vite + TypeScript)

## Install Dependencies
```bash
cd frontend
```
```bash
npm install
```
## Run Frontend Dev Server
```bash
npm run dev
```
## Build Frontend
```bash
npm run build
```
## Preview Build
```bash
npm run preview
```
## Lint
```bash
npm run lint
```

# 🐳 Docker (Optional)
## Start All Services
```bash
docker compose up --build
```
Run in Background
```bash
docker compose up -d
```
## Stop Services
```bash
docker compose down
```
# ⚡ Quick Start
## Backend
```bash
dotnet watch run --project backend/src/Api/Api.csproj
```
## Frontend
```bash
cd frontend
npm install
npm run dev
```