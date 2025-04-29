# API-1


# 📞 Call Log API

A simple REST API for logging and retrieving phone call records, built using FastAPI and Python.

## 🚀 Features

- Add new call logs with metadata
- Retrieve all call records
- Filter call logs by phone number, call type, or date
- Fast and lightweight using FastAPI
- Swagger UI for interactive documentation

## 🛠️ Tech Stack

- Python 3.8+
- FastAPI
- Uvicorn (ASGI server)
- SQLite / CSV / In-memory (customizable storage)
- Pydantic (for data validation)

## 📂 Project Structure

```
call-log-api/
├── main.py             # FastAPI app with all endpoints
├── models.py           # Pydantic models for request/response
├── storage.py          # In-memory or file-based storage logic
├── utils.py            # (Optional) helper functions
├── requirements.txt    # Python dependencies
└── README.md           # This file
```

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/call-log-api.git
cd call-log-api
```

2. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the API Server

```bash
uvicorn main:app --reload
```

Visit Swagger UI at:

http://127.0.0.1:8000/docs


