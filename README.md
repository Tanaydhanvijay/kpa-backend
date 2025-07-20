# KPA Form Data API

### 🛠 Tech Stack
- Python
- FastAPI
- PostgreSQL
- SQLAlchemy

### 🚀 Setup Instructions
1. Clone the repo or unzip the code.
2. Create virtual environment:  
   `python -m venv venv && source venv/bin/activate` (or `venv\Scripts\activate` on Windows)
3. Install dependencies:  
   `pip install -r requirements.txt`
4. Start the server:  
   `uvicorn app.main:app --reload`

### 📌 Implemented APIs

1. **POST /form_data/create**
   - Accepts a JSON body with personal and address info
   - Stores the data in PostgreSQL

2. **GET /form_data/all**
   - Returns all submitted form data

### ✅ Notes
- Swagger Docs: `http://127.0.0.1:8000/docs`
- Tested via Postman
- `.env` used for DB config (optional)
