# SQLite Fundamentals with Python

This project is a beginner-friendly tutorial and reference on how to use **SQLite** with **Python** in a Jupyter Notebook. It covers essential **CRUD operations** (Create, Read, Update, Delete) using raw SQL and Python's built-in `sqlite3` module.

---

## 📂 Project Structure
```text
├── sqlite_fundamental.ipynb # Manual CRUD queries
├── sqlite_fundamental_with_function.ipynb # Reusable CRUD functions
├── users_export.csv # Exported user data (optional)
├── README.md # Project documentation
```


---

## 🚀 Features Covered

### ✅ CRUD Operations

- Create SQLite database and table
- Insert single and multiple users
- Read all users or by ID
- Update user information
- Delete user

### 🛠️ Function-Based Abstraction

- Reusable Python functions for all operations
- SQLite connection handled with best practices
- Error handling (e.g., duplicate email)

### 📊 Enhancements

- Read results into Pandas DataFrame
- Export user data to CSV
- Search users by name using `LIKE`

---

## 📒 Notebooks

### `sqlite_fundamental.ipynb`

- Step-by-step manual execution of SQL commands
- Great for learning how SQL works

### `sqlite_fundamental_with_function.ipynb`

- Modular functions for all operations
- Clean and reusable structure
- Ideal for integrating into larger Python projects

---

## 💡 Requirements

- Python 3.x
- `sqlite3` (built-in with Python)
- `pandas`
- Jupyter Notebook

Install dependencies (if needed):

```bash
pip install pandas notebook
```
---

## 🏁 How to Run

1. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open and run:

   * `sqlite_fundamental.ipynb` to follow raw SQL examples
   * `sqlite_fundamental_with_function.ipynb` to use Python functions

---

## 📝 Example Usage

```python
create_table()
insert_user("Alice", 30, "alice@example.com")
print(get_all_users_df())
search_users_by_name("Ali")
export_users_to_csv()
```

---

## 📦 Output

* SQLite database file: `example.db`
* CSV export file: `users.csv`

---

## 🧑‍💻 Author

Md. Jahidul Alam
GitHub: [jahidsagar](https://github.com/jahidsagar)

---

## 📜 License

This project is open source and free to use for educational purposes.

```

---

You can save this as `README.md` in your repo.

Let me know if you want a version with screenshots, badges, or setup instructions for a specific OS or cloud platform (like Binder or Replit)!
```
