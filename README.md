# ParkirUang
## Personal Finance Management System
**ParkirUang** is a Java-based personal finance management system designed to help users manage income, expenses, and savings.

## Business Objective
Managing personal finances can be challenging when income and expenses are tracked inconsistently or without long-term analysis.
ParkirUang aims to provide a structured approach to recording financial transactions and generating meaningful summaries to support better financial awareness and decision-making.

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
- Currently under active development
- Current phase: Phase 1 – Preparation

## Tech Stack
- **Java 17**
- **SQLite** (via JDBC)

## Project Structure (planned)
```
ParkirUang/
├── docs/ # Documentation files (categories, ERD, format-date, etc.)
├── src/ # Java source code
├── schema.sql # Database schema
├── README.md # Project description
└── .gitignore # Git ignore rules for Java projects
```

## Documentation

- Requirements
- Database Design (ERD)
- Database Schema
- Test Cases

## Roadmap

### Phase 1 – Preparation
- Define initial transaction categories (income & expense)
- Decide on date format (`YYYY-MM-DD`)
- Design database structure and create ERD
- Define database schema
- Initialize GitHub repository and documentation

### Phase 2 – Core System Implementation
- Implement database schema & connection
- Add transaction (CRUD operations)
- View transactions by month
- Monthly summary calculations (income, expense, saving, saving rate)
- Implement command-line interface for user interaction

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
