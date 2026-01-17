# Penny — Offline Group Expense Manager

Open-source · Free · Privacy-first

---

## Overview

**Penny** is a lightweight, offline-first group expense manager built for students, roommates, and small groups.

It focuses on **correct expense splitting**, **local-only data storage**, and **predictable behavior**.  
No accounts, no subscriptions, no cloud dependency.

---

## Why Penny

Most expense apps:
- Require internet and user accounts
- Lock exports behind paywalls
- Hide calculation logic

Penny avoids all of that by design.

---

## Features

- Multiple users and expense categories
- Equal and unequal expense splits
- Deterministic balance calculation
- Edit and delete expense records
- 100% offline local storage (JSON / SQLite)
- Export and import data (JSON, Excel)
- Monthly expense grouping

---

## Architecture

```text
UI Layer (Flutter)
Service Layer (Expense logic, validation)
Data Layer (Local JSON / SQLite)
