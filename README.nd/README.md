# Authentication System (Next.js + FastAPI)

A simple authentication system built using **Next.js** for the frontend and **FastAPI** for the backend. This system includes functionality for user signup and login, showcasing modern web development practices with a clean and responsive UI.

---

## **Features**
- User **Signup** with form validation.
- User **Login** with success/error handling.
- **Token-based authentication** (can be extended to use JWT for real-world applications).
- Clean and responsive UI with CSS Modules.
- **Frontend:** Next.js
- **Backend:** FastAPI (SQLite used for storage).

---

## **Folder Structure**
```plaintext
authentication-system/
│
├── backend/                # Backend API built with FastAPI
│   ├── app/
│   │   ├── __init__.py     # Python package initialization
│   │   ├── main.py         # FastAPI entry point
│   │   ├── models.py       # Database models
│   │   ├── database.py     # Database connection
│   │   ├── schemas.py      # Request/response schemas
│   │   └── auth.py         # Signup and login logic
│   ├── requirements.txt    # Python dependencies
│
├── frontend/               # Frontend built with Next.js
│   ├── pages/              # Next.js pages
│   │   ├── index.js        # Login page
│   │   ├── signup.js       # Signup page
│   │   ├── dashboard.js    # Dashboard for logged-in users
│   ├── styles/             # CSS Modules for styling
│   │   ├── globals.css     # Global styles
│   │   ├── index.module.css # Scoped styles for login
│   │   ├── signup.module.css # Scoped styles for signup
│   └── package.json        # Frontend dependencies
│
└── README.md               # Documentation for the project
