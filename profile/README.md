# JAVDEX

**A modern catalog platform for discovering, organizing, and exploring titles, artists, releases, and media.**

---

## About JAVDEX

JAVDEX is a web-based catalog platform focused on providing structured information and an organized browsing experience.

Our goal is to build a clean, modern, and scalable platform with dedicated tools for both users and administrators.

## Projects

### 🌐 JAVDEX Web

The public-facing application where users can browse and explore the JAVDEX catalog.

**Stack:**

* React
* Vite
* JavaScript
* Supabase

### ⚙️ JAVDEX Admin

A dedicated administration panel for managing the JAVDEX platform.

**Stack:**

* React
* Vite
* JavaScript
* Supabase

## Architecture

```text
                    JAVDEX
                       │
             ┌─────────┴─────────┐
             │                   │
       JAVDEX Web          JAVDEX Admin
       React + Vite        React + Vite
             │                   │
             └─────────┬─────────┘
                       │
                    Supabase
             ┌─────────┼─────────┐
             │         │         │
         Database     Auth     Storage
```

## Technology

| Area             | Technology         |
| ---------------- | ------------------ |
| Frontend         | React + Vite       |
| Language         | JavaScript         |
| Database         | PostgreSQL         |
| Backend Services | Supabase           |
| Authentication   | Supabase Auth      |
| Storage          | Supabase Storage   |
| Security         | Row Level Security |
| Version Control  | Git + GitHub       |

## Development

JAVDEX is currently under development.

The architecture and features will continue to evolve as the platform grows.

---

**JAVDEX-WEBAPP**

Building the JAVDEX ecosystem.
