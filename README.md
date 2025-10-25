# 🧠 FastAPI To-Do-List App

### A lightweight REST API built with **FastAPI** and **Python** for creating and managing simple items.

This project demonstrates the fundamentals of building and structuring a backend API with **FastAPI** — including request models, routing, and error handling — all in an elegant and high-performance Python framework.

---

## 🚀 Features
- ⚡ Built with **FastAPI** — one of the fastest Python web frameworks available  
- 🧱 **CRUD-style endpoints** for creating and retrieving items  
- 🧾 **Automatic API documentation** via **Swagger UI** and **ReDoc**  
- 💡 Demonstrates clean use of **Pydantic models** for data validation  
- 🧠 Ideal starter project for understanding FastAPI fundamentals

---

## 🧰 Tech Stack

| Category | Tools Used |
|-----------|------------|
| **Framework** | FastAPI |
| **Language** | Python 3.10+ |
| **Server** | Uvicorn |
| **Data Handling** | Pydantic models & in-memory list |
| **Version Control** | Git & GitHub |
| **Deployment (optional)** | Vercel / Render / Railway |

---

## ⚙️ Installation & Setup

```bash
# 1️⃣ Clone the repository
git clone https://github.com/MarquisPierre/Fast_API_App.git
cd Fast_API_App

# 2️⃣ Create and activate a virtual environment
python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows

# 3️⃣ Install dependencies
pip install fastapi uvicorn pydantic

# 4️⃣ Run the FastAPI server
uvicorn main:app --reload
```
📡 API Endpoints
| Method   | Endpoint           | Description                                  |
| -------- | ------------------ | -------------------------------------------- |
| **GET**  | `/`                | Returns a simple “Hello World” message       |
| **POST** | `/items`           | Adds a new item (requires JSON body)         |
| **GET**  | `/items`           | Returns a list of items (default limit = 10) |
| **GET**  | `/items/{item_id}` | Returns a specific item by its ID            |

Example JSON body for POST /items
```
{
  "text": "Buy groceries",
  "is_done": false
}

```

📁 Project Structure


```
fastapi-todo/
│
├── main.py
├── requirements.txt
└── README.md
```
🧠 What I Learned

Through this project, I gained hands-on experience with:

Building REST APIs using FastAPI

Structuring endpoints and using Pydantic models for validation

Managing data in-memory and handling HTTP exceptions

Creating self-documenting APIs with Swagger UI

Running and testing FastAPI apps locally with Uvicorn



