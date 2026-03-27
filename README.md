# Spendly - Personal Expense Tracker

A Flask-based web application for tracking personal expenses and understanding spending patterns.

## Project Overview

**Spendly** helps users track every rupee, log expenses, and take control of their financial life. The application provides category-based expense tracking with visual breakdowns and monthly summaries.


## Project Structure

```
expense-tracker/
├── app.py                  # Main Flask application
├── database/
│   ├── __init__.py
│   └── db.py               # Database layer (placeholder)
├── templates/
│   ├── base.html           # Base template with nav/footer
│   ├── landing.html        # Landing page
│   ├── login.html          # Login page
│   └── register.html       # Registration page
├── static/
│   ├── css/                # Stylesheets
│   └── js/                 # JavaScript files
├── requirements.txt        # Python dependencies
├── .gitignore
└── README.md
```

## Routes

| Route | Method | Status | Description |
|-------|--------|--------|-------------|
| `/` | GET | Done | Landing page |
| `/register` | GET | Done | Registration page |
| `/login` | GET | Done | Login page |
| `/logout` | GET | Placeholder | User logout |
| `/profile` | GET | Placeholder | User profile |
| `/expenses/add` | GET/POST | Placeholder | Add new expense |
| `/expenses/<id>/edit` | GET/POST | Placeholder | Edit expense |
| `/expenses/<id>/delete` | POST | Placeholder | Delete expense |

## Setup & Installation

### Prerequisites
- Python 3.11+
- uv (recommended) or pip

### Installation

1. Clone the repository
2. Create and activate virtual environment:
   ```bash
   uv venv
   source .venv/Scripts/activate  # Windows
   ```

3. Install dependencies:
   ```bash
   uv pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open browser to `http://localhost:5001`