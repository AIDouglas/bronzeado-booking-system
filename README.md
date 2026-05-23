# Bronzeado Booking System

Sistema de automatización de reservas para empresa de bronceado.

## Características

- Chatbot WhatsApp
- Reservas automáticas
- Integración Google Calendar
- Pagos online
- Confirmaciones automáticas
- Panel administrativo
- Landing page

---

# Arquitectura

Monorepo basado en:

- NestJS
- Next.js
- PostgreSQL
- Prisma
- WhatsApp Cloud API
- Google Calendar API
- Wompi

---

# Estructura

/apps
- api       → Backend NestJS
- web       → Frontend Next.js
- admin     → Panel administrativo

/packages
- ui
- config
- types

---

# Requisitos

- Node.js >= 20
- pnpm
- PostgreSQL

---

# Instalación

```bash
pnpm install
```

---

# Ejecutar proyecto

## Backend

```bash
cd apps/api
pnpm run start:dev
```

## Frontend

```bash
cd apps/web
pnpm run dev
```

---

# Variables de entorno

Crear:

```bash
.env
```

---

# Tecnologías

- NestJS
- Next.js
- TailwindCSS
- PostgreSQL
- Prisma ORM
- WhatsApp Cloud API
- Google Calendar API
- Wompi

---

# Licencia

MIT