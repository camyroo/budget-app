README.md

```markdown
# FastAPI + Next.js Project

This repository contains a **FastAPI backend** and a **Next.js frontend**.

## Project Structure

```
myfastapi/
├─ backend/         # FastAPI backend
├─ frontend/        # Next.js frontend
├─ venv/           # Python virtual environment
```

---

## Backend (FastAPI)

### 1. Activate the virtual environment

```bash
source ../venv/bin/activate   # On WSL/Linux
# On Windows CMD/Powershell: venv\Scripts\activate
```

### 2. Start the FastAPI server

```bash
cd backend
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```

- Server runs at: `http://localhost:8000`
- API docs: `http://localhost:8000/docs`

---

## Frontend (Next.js)

### 1. Install dependencies

```bash
cd ../frontend
npm install
```

### 2. Start the development server

```bash
npm run dev
```

- Frontend runs at: `http://localhost:3000`

---

## Quick Start

1. **Backend**: Activate venv → `cd backend` → `uvicorn main:app --reload --host 0.0.0.0 --port 8000`
2. **Frontend**: `cd frontend` → `npm install` → `npm run dev`
3. **Access**: Backend at `:8000`, Frontend at `:3000`
```