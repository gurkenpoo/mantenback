# Proyecto Fullstack - NestJS + Prisma + Postgres + Next.js

## 📌 Descripción
Este proyecto es una aplicación fullstack compuesta por:
- **Backend**: API construida con [NestJS](https://nestjs.com/), utilizando [Prisma](https://www.prisma.io/) como ORM y [PostgreSQL](https://www.postgresql.org/) como base de datos.
- **Frontend**: Interfaz de usuario desarrollada con [Next.js](https://nextjs.org/) y [React](https://react.dev/).

El objetivo es crear una arquitectura escalable, mantenible y moderna, con proyectos separados para frontend y backend.

---

## 🛠️ Tecnologías principales
- **Backend**
  - NestJS
  - Prisma ORM
  - PostgreSQL
  - Docker & Docker Compose
  - JWT para autenticación

- **Frontend**
  - Next.js (React + TypeScript)
  - TailwindCSS / Chakra UI (opcional para estilos)
  - Axios / React Query para consumo de API
  - NextAuth para autenticación

---

## 📂 Estructura de repositorios
El proyecto está dividido en dos repositorios independientes:

- `backend/`
  - API en NestJS
  - Prisma + migraciones
  - Configuración de Docker Compose para levantar backend + base de datos

- `frontend/`
  - Aplicación en Next.js
  - Configuración de entorno para consumir la API del backend

---
