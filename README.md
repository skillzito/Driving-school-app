# Driving School App

A management application for a driving school.

## Overview

This project helps driving schools manage:
- students
- instructors
- vehicles
- lesson scheduling
- attendance
- payments
- reports

## Recommended stack

- Frontend: Next.js + TypeScript
- Backend: Next.js API routes
- Database: PostgreSQL
- ORM: Drizzle
- Auth: NextAuth or Supabase Auth
- Hosting: Vercel
- Database hosting: Supabase

## Project structure

```bash
/
├── app/
│   ├── api/
│   │   └── health/route.ts
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   └── dashboard-card.tsx
├── lib/
│   └── utils.ts
├── public/
├── package.json
├── tsconfig.json
├── next.config.js
├── .gitignore
├── README.md
└── .env.example
