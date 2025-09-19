# Library Management System Database

A complete relational database system for managing library operations including books, members, staff, and transactions.

## Features

- **10 Tables** with proper relationships
- **All Constraint Types**: PRIMARY KEY, FOREIGN KEY, NOT NULL, UNIQUE, CHECK
- **Relationship Types**: One-to-One, One-to-Many, Many-to-Many
- **Performance Optimization**: Indexes on frequently queried columns

## Database Schema

### Core Tables
- `authors` - Author information
- `categories` - Book categories
- `publishers` - Publisher details
- `books` - Book catalog
- `members` - Library members
- `staff` - Library staff

### Relationship Tables
- `borrowings` - Book borrowing transactions
- `reservations` - Book reservations
- `book_authors` - Books with multiple authors
- `member_profiles` - Extended member information

## Installation

1. Install MySQL
2. Run the SQL file:
```sql
mysql -u username -p < library_management_system.sql
```

## Usage

The database supports:
- Book catalog management
- Member registration and profiles
- Borrowing and return tracking
- Reservation system
- Staff management
- Fine calculation