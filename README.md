# DBMS.SQL_BOLT

A collection of SQL scripts, exercises, and examples inspired by **SQLBolt** to help you learn and practice SQL concepts for Database Management Systems (DBMS).

## 📌 Features
- Beginner to advanced SQL queries
- Covers **DDL**, **DML**, **DQL**, and **DCL** commands
- Realistic sample database schema
- Practice exercises with solutions
- Compatible with MySQL, PostgreSQL, and SQLite

## 📂 Project Structure

dbms.sql_bolt/
│
├── README.md          # Project documentation
├── schema.sql         # Database schema creation script
├── data.sql           # Sample data insertion script
├── exercises.sql      # Practice queries
└── solutions.sql      # Suggested solutions

## 🛠️ Requirements
- **Database Engine**: MySQL / PostgreSQL / SQLite
- **SQL Client**: CLI or GUI (e.g., DBeaver, MySQL Workbench, pgAdmin)

## 🚀 Setup Instructions
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/dbms.sql_bolt.git
   cd dbms.sql_bolt



Create the database
SqlCREATE DATABASE sql_bolt;



Load the schema and data
Bashmysql -u root -p sql_bolt < schema.sql
mysql -u root -p sql_bolt < data.sql



Start practicing

Open exercises.sql in your SQL client
Run queries and compare with solutions.sql



📖 Topics Covered

Creating and altering tables
Inserting, updating, and deleting data
Filtering with WHERE, LIKE, IN, BETWEEN
Sorting and limiting results
Aggregate functions (COUNT, SUM, AVG, etc.)
Grouping with GROUP BY and HAVING
Joins (INNER, LEFT, RIGHT, FULL)
Subqueries and nested queries
Views and indexes

🧠 Example Query
Sql-- Find all users older than 30
SELECT id, name, age
FROM users
WHERE age > 30;

📜 License
This project is licensed under the MIT License — feel free to use and modify.
🤝 Contributing
Pull requests are welcome!
If you find an issue or have an improvement idea, open an issue in the repository.

Happy Learning SQL! 🚀

---

If you want, I can also **create the `schema.sql` and `data.sql` files** so that this `README.md` is fully runnable with a working database.  

Do you want me to prepare those SQL files next?
