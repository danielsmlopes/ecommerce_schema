# Week 1 — workshop1.sql

This folder contains `workshop1.sql`, a PostgreSQL setup script that creates the `week1_workshop` database and a simple e‑commerce style schema (products, categories, suppliers, customers, employees, orders, join tables, territories, offices, and US states) with appropriate primary and foreign key constraints. It's intended for classroom exercises on DDL, relationships, and referential integrity.

## Quick start

1. Ensure PostgreSQL is installed and running.
2. From the command line, run the script with `psql`:

```bash
psql -f ecommerce_schema/workshop1.sql
```

Or connect to your Postgres server and run the file from within `psql`:

```bash
psql
\i ecommerce_schema/workshop1.sql
```

The script will terminate any existing connections to a database named `week1_workshop`, drop and recreate it, set session parameters, create tables, and add foreign key constraints. The file contains TODO comments for extension during exercises.
