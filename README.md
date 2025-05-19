# schema_value_lookup
Easily locate where a value exists in your MySQL database — table, column

# 🔍 Find Value in MySQL Database Schema

This Python utility helps you search for a specific value across **all tables and columns** in a MySQL database.  
It's especially useful for developers, data analysts, or anyone working with large databases who doesn't have full knowledge of the schema.

---

## 📌 Features

- Search any value in all text-based columns (`VARCHAR`, `TEXT`, etc.)
- Returns the table name and column name where the value is found
- Easy to configure with your own MySQL credentials
- Beginner-friendly and schema-agnostic

---

## 💡 When Should You Use This?

This tool is especially handy in the following situations:

- 🔍 **You don't know the schema**: You just got access to a new or legacy database and have no clue where data is stored.
- 🛠️ **Debugging a production issue**: You have a value (like a PO number, customer ID, or transaction code) and need to figure out where it’s hiding.
- 📊 **Building reports or dashboards**: Analysts trying to connect the dots between disconnected tables can use this to locate key data fields.

In short, whenever you're stuck thinking:  
🧠 *“Where the hell is this value stored?”*  
— this notebook is your quick fix.

---

## 🛠️ Requirements

- Python 3.x
- `mysql-connector-python` (or `pymysql`, based on your implementation)

Install dependencies:

```bash
pip install mysql-connector-python
