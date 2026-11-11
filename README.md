# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some Oxlint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is enabled on this template. See [this documentation](https://react.dev/learn/react-compiler) for more information.

Note: This will impact Vite dev & build performances.

## Expanding the Oxlint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and Oxlint's TypeScript related rules in your project.
# FastAPI × PostgreSQL

### Python Backend Development | REST API | Database Integration

A Python backend project built with **FastAPI, PostgreSQL, and SQLAlchemy**, focused on establishing a reliable connection between an API application and a relational database.

The project demonstrates backend initialization, database engine configuration, and the foundation for developing database-driven REST APIs.

---

## Overview

This repository explores the integration of FastAPI with PostgreSQL through SQLAlchemy. It provides a starting point for building structured backend applications using modern Python technologies.

## Technology Stack

| Technology | Role |
|---|---|
| Python | Backend language |
| FastAPI | API framework |
| PostgreSQL | Relational database |
| SQLAlchemy | Database toolkit and ORM |
| Uvicorn | ASGI server |

## System Architecture

```text
       API Client
           |
           v
      FastAPI App
           |
           v
    SQLAlchemy Engine
           |
           v
       PostgreSQL
```

## Project Structure

```text
FastAPi-postgre/
│
├── main.py
├── .gitignore
└── README.md
```

## Local Development

**1. Clone the repository**

```bash
git clone https://github.com/alisafdarraza737-sketch/FastAPi-postgre.git
cd FastAPi-postgre
```

**2. Create and activate a virtual environment**

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

**3. Install dependencies**

```bash
pip install fastapi uvicorn sqlalchemy psycopg2-binary
```

**4. Configure PostgreSQL**

Set the database connection string in `main.py`:

```python
DATABASE_URL = "postgresql://postgres:YOUR_PASSWORD@localhost:5432/YOUR_DATABASE"
```

Replace the placeholders with your PostgreSQL credentials.

**5. Start the development server**

```bash
uvicorn main:app --reload
```

## API Documentation

Once the application is running:

| Resource | Endpoint |
|---|---|
| API Server | `http://127.0.0.1:8000` |
| Swagger UI | `http://127.0.0.1:8000/docs` |
| ReDoc | `http://127.0.0.1:8000/redoc` |

## Engineering Focus

- FastAPI application initialization
- PostgreSQL connection configuration
- SQLAlchemy engine integration
- Python backend environment setup
- Relational database fundamentals

## Roadmap

- [ ] Database models and schemas
- [ ] Database session management
- [ ] RESTful CRUD endpoints
- [ ] Request and response validation
- [ ] Authentication and authorization
- [ ] Automated API testing
- [ ] Environment-based configuration

## Author

**Ali Safdar Raza**

*Python Developer | Backend Development | Data Analytics | AI/ML*

[GitHub](https://github.com/alisafdarraza737-sketch) · [LinkedIn](https://www.linkedin.com/in/alisafdar-raza-07984b390/)

---

<sub>Developed as part of my journey in Python backend engineering.</sub>
