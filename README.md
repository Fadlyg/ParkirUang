# ParkirUang
**Parkir Uang** is a simple CLI-based personal finance tracker built with Java and SQLite.  
It helps you record income and expenses, view monthly summaries, and calculate your saving rate — all from the command line.

## Features (MVP)
- Add transactions (income / expense)
- View transactions by month
- Edit and delete transactions
- Monthly summary:
  - Total income
  - Total expenses
  - Savings (income - expenses)
  - Saving rate (%)

## Status
Currently in **Phase 1 – Preparation**.

## Tech Stack
- **Java 17**
- **SQLite** (via JDBC)

## Project Structure (planned)
ParkirUang/
├── docs/ # Documentation files (categories, ERD, format-date, etc.)
├── src/ # Java source code
├── schema.sql # Database schema
├── README.md # Project description
└── .gitignore # Git ignore rules for Java projects


## Roadmap

### Phase 1 – Preparation
- Define initial transaction categories (income & expense)
- Decide on date format (`YYYY-MM-DD`)
- Create database structure (ERD)
- Initialize GitHub repository and documentation

### Phase 2 – Backend (CLI)
- Implement database schema & connection
- Add transaction (CRUD operations)
- View transactions by month
- Monthly summary calculations (income, expense, saving, saving rate)

### Phase 3 – Polishing
- Input validation
- Code refactoring & documentation
- Manual testing

### Phase 4 – Optional UI/UX Upgrade
- JavaFX Desktop Application **or** Spring Boot Web App
- Dashboard with charts and filters
- Category and budget management

## License
This project is licensed under the MIT License.
