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
