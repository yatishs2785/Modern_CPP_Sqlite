This project demonstrates a lightweight SQLite-based database engine implemented in C/C++.
It provides a simple interface for creating tables, inserting records, querying data, and managing persistence.
The goal is to showcase modular design, clean documentation, and educational clarity for students and developers.

⚙️ Features
- Database Initialization: Create and connect to SQLite databases.
- Schema Management: Create tables with user-defined columns.
- CRUD Operations:
- Insert new records
- Read/query data with filters
- Update existing records
- Delete records
- Query Execution: Run raw SQL queries directly.
- Error Handling: Safe execution with descriptive error messages.
- Modular Codebase: Separation of concerns (database connection, query execution, utilities).
- Educational Examples: Sample queries and datasets included.

Project Structure
SQLiteDB/
│── src/
│   ├── main.c          # Entry point
│   ├── db_manager.c    # Core DB functions
│   ├── db_manager.h    # Header file
│   └── utils.c         # Helper utilities
│── examples/
│   ├── sample_queries.sql
│   └── sample_data.db
│── README.md
│── Makefile
