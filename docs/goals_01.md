## Goal setting:

- Create a basic Python CLI based script that can read user inputs from user about their present day expenses and then store it in a file.
    - The script should consider the following parameters:
      - Date (asked only once when user is running script for first time)
        - Expense
        - Category
        - Description (optional)
        - Amount


## - Future things:
- Make it possible to **create** and **select tags** from terminal (probably use interactive shell or any libraries like `prompt_toolkit` or `click`).
- Let user adjust amount of past days (there are scope for mistakes in entering amount 🤷).
- Let user add export the saved data to a CSV file.
- Use `sqlite3` to store the data in a database.
  - At later point of time we can shift to `SQLAlchemy` for better management of database.
