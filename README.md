# Tiger Bank - Banking System

A Python-based banking application with Tkinter GUI and MySQL database backend. Elite 102 Code2College project.

## Features

- Create accounts with PIN authentication
- Secure login with account number and 4-digit PIN
- Deposit and withdraw money with validation
- Check account balance
- Real-time database updates

## Tech Stack

- **Frontend**: Python Tkinter
- **Backend**: Python
- **Database**: MySQL
- **Testing**: unittest with mocking

## Setup

1. **Install dependencies**
   ```bash
   pip install mysql-connector-python python-dotenv
   ```

2. **Create `.env` file** with database credentials:
   ```
   DB_HOST=localhost
   DB_USER=your_username
   DB_PASSWORD=your_password
   DB_NAME=BankingSystem
   ```

## Usage

```bash
python main.py
```

Run tests:
```bash
python -m unittest tests.tests
```

---

**Note**: Ensure your MySQL database and required tables are set up before running the application. Reference the `db.py` file for the expected database schema.