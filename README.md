# Deiivcouple
textnow_clone/
│
├── app/
│   ├── __init__.py
│   ├── main.py                # FastAPI entrypoint
│   ├── models.py              # SQLAlchemy models (User, Message, Call, etc.)
│   ├── schemas.py             # Pydantic schemas for API
│   ├── crud.py                # Database operations
│   ├── deps.py                # Dependencies (e.g., get_db, auth)
│   ├── auth.py                # Authentication logic (JWT, OAuth2)
│   ├── sms.py                 # SMS logic (integrate Twilio/Nexmo here)
│   ├── call.py                # Voice call logic (e.g., Plivo, Twilio, Asterisk)
│   ├── utils.py               # Helper utilities
│   ├── config.py              # Settings (env variables, secrets)
│   └── tests/
│       └── ...                # Pytest test scripts
│
├── Dockerfile                 # To build/run app in Docker
├── docker-compose.yml         # For multi-container setup (app + db + others)
├── requirements.txt           # Python dependencies
├── README.md                  # Project instructions
└── .env.example               # Example environment variables
