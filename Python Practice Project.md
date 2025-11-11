# Practice Projects

## 1. Quiz App
**Requirements:**
- Store questions and answers in a dictionary or JSON file.
- Ask user questions one by one.
- Keep score and show the result at the end.

## 2. Portfolio Website (Flask)
**Requirements:**
- Build a simple personal portfolio with Flask.
- Have pages like `Home`,`Projects`, and `Contact.`
- Load project data from a JSON file.

## 3. Expense Tracker
**Requirements:**
- Add, view, and delete expenses with date, category, and amount.
- Store data in a CSV or SQLite database.
- Calculate total and category-wise summaries.

**Required Features**

Implement all of the following to call the project complete:  
Add an expense with fields:
- id (unique)
- date (ISO YYYY-MM-DD)
- amount (float)
- category (string)
- description (string, optional)
- List/view all expenses (paginated or limited view for CLI).
- Delete an expense by id.
- Edit/update an expense by id.

Persist data in:  
- a CSV file (expenses.csv)   
Show summary statistics:
- Total expenses (all time)
- Total by category
- Total for a date range

**Basic input validation and error handling (e.g., valid date, non-negative amount).**