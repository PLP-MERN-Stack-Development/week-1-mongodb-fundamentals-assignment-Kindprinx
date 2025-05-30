# 📚 MongoDB Bookstore Project – PLP Assignment

This project demonstrates MongoDB fundamentals using a fictional **Bookstore** database. It covers CRUD operations, advanced queries, aggregation pipelines, and indexing — all using a sample dataset of 13 books.

---

## 🛠️ Setup Instructions

### Prerequisites:
- MongoDB installed locally **OR**
- Access to a MongoDB Atlas Cluster
- MongoDB Shell (`mongosh`) or GUI (e.g., MongoDB Compass)

### Steps:

1. Clone or download this project.
2. Open your terminal and navigate to the project folder.
3. Run the following command to insert the books:
   ```bash
   mongosh < insert_books.js

📦 Sample Book Fields
Each book document includes the following fields:

title (String)

author (String)

genre (String)

published_year (Number)

price (Decimal)

in_stock (Boolean)

pages (Number)

publisher (String)

✅ Features & Queries
🔹 CRUD Operations
Find all books by genre, author, or year

Update price of a book

Delete a book by title

🔹 Advanced Queries
Combine conditions (e.g., in stock & recent)

Projection (select fields only)

Sort books by price (asc/desc)

Pagination using limit() and skip()

🔹 Aggregation Pipelines
Average book price by genre

Most published author

Books grouped by publication decade

🔹 Indexing & Performance
Create single and compound indexes

Use .explain() to analyze performance
 Author
Kindness Ebeneza 