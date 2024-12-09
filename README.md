# Expense Tracking System

This project is an **Expense Tracking System** built using Python. It allows users to add, update, and analyze their expenses based on categories and months. The system leverages a backend API built with FastAPI and a user-friendly frontend created using Streamlit.

## Features
- **Backend**: Developed with FastAPI, supporting CRUD operations for managing expenses.
- **Frontend**: Built with Streamlit for a clean and interactive user interface.
- **Database**: MySQL is used to store expense data.
- **Testing**: Pytest was used for backend testing.
- **Analytics**: Provides insights into expenses by category and month.

---

## Tech Stack
- **Backend Framework**: FastAPI
- **Frontend Framework**: Streamlit
- **Database**: MySQL
- **Testing**: Pytest
- **Additional Libraries**: Pydantic, Pandas, Requests, Uvicorn

---

## Installation and Setup

### Prerequisites
Ensure you have Python 3.9+ installed.

### Steps to Run the Project:
1. Clone the repository:
   ```bash
   git clone <repository-url>

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the backend server:
   ```bash
   uvicorn main:app --reload
   
4. Run the Streamlit app:
   ```bash
   streamlit run app.py

## Dependencies

streamlit==1.35.0,
fastapi==0.112.2,
pydantic==1.10.9,
uvicorn==0.30.6,
mysql-connector-python==8.0.33,
pandas==2.0.2,
requests==2.31.0,
pytest==8.3.2

---

## Project Workflow

### Backend Development:
- Built using FastAPI.
- Tested API calls with tools like Postman.

### Frontend Development:
- Built using Streamlit.
- Integrated with the backend API.





