# S3Z 2.0 - Full Stack Notes App

A full-stack notes application built with Django REST Framework backend and React frontend.

## Features

- User authentication (login/register)
- Create, read, and delete notes
- Protected routes
- JWT token authentication
- Responsive design

## Tech Stack

### Backend
- Django 5.2.7
- Django REST Framework
- JWT Authentication
- SQLite database (development)

### Frontend
- React 19.1.1
- Vite
- React Router
- Axios for API calls

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run migrations:
   ```bash
   python manage.py migrate
   ```

4. Start the Django development server:
   ```bash
   python manage.py runserver
   ```

The backend will be available at `http://localhost:8000`

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install Node.js dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

The frontend will be available at `http://localhost:5173` (or another port if 5173 is in use)

## Environment Variables

Create a `.env` file in the frontend directory with:
```
VITE_API_URL=http://localhost:8000
```

## Project Structure

```
s3z-2.0/
├── backend/           # Django REST API
├── frontend/          # React application
├── env/              # Python virtual environment
└── README.md
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).