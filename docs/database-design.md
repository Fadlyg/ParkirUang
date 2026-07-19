# Database Design

## Overview

This document describes the database design for ParkirUang.

## Business Requirements & Rules

### Core Features
- **Multi-Account Management:** The system must be capable of managing multiple independent financial accounts (e.g., Bank Account, E-Wallet, Cash).
- **Hierarchical Categorization:** Transaction classification must support a nested, multi-level structure (Parent-Child) to allow granular reporting (e.g., Transportation -> Fuel -> Diesel).

### Transaction Types & Business Logic
The system must recognize and process three distinct financial activities based on the following rules:
1.  **Income:** An activity that increases the balance of a single specific account. A category assignment is required.
2.  **Expense:** An activity that decreases the balance of a single specific account. A category assignment is required.
3.  **Transfer:** An activity representing the internal movement of funds, which simultaneously decreases the balance of the source account and increases the balance of the destination account. This activity does not alter net wealth and does not require a category assignment.

## Entities

### Transaction

Description:
Stores all income and expense transactions.

### Category

Description:
Defines categories for income and expense transactions.

## Relationships

- One category can have many transactions.
- Each transaction belongs to one category.

## Entity Relationship Diagram (ERD)

(To be added)