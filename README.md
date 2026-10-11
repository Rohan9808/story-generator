# 📚 AI Story Generator

An AI-powered interactive storytelling application that generates stories and allows users to explore different story paths through interactive choices.

## ✨ Features

- **AI Story Generation** — Generate stories dynamically using AI.
- **Interactive Storytelling** — Make choices that influence how the story progresses.
- **Story Navigation** — Navigate between story nodes based on available options.
- **Story Completion** — Load and play complete stories.
- **Backend API** — RESTful APIs built with FastAPI.
- **Frontend Application** — Interactive user interface built with React.

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- Axios
- React Router

### Backend
- Python
- FastAPI
- Pydantic
- SQLAlchemy / SQLModel
- Database integration
- AI/LLM integration

## 📁 Project Structure

```text
story-generator/
├── backend/
│   ├── app/
│   ├── requirements.txt
│   └── ...
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
└── README.md
```

*The directory structure may vary depending on the current implementation.*

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- Python 3.11 or a compatible version
- Node.js and npm
- Git

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd story-generator
```

### 2. Set Up the Backend

Navigate to the backend directory:

```bash
cd backend
```

Create and activate a virtual environment.

**Windows PowerShell:**

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Configure the required environment variables in a `.env` file, such as database connection details and AI provider API keys.

Start the FastAPI development server using your application's entry point. For example, if the FastAPI instance is defined as `app` in `main.py`:

```bash
uvicorn main:app --reload
```

The backend API will be available at:

`http://127.0.0.1:8000`

Interactive API documentation:

`http://127.0.0.1:8000/docs`

### 3. Set Up the Frontend

Open another terminal and navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Configure the frontend API base URL to point to your local backend.

Start the development server:

```bash
npm run dev
```

Open the local URL displayed in your terminal.

## ⚙️ Environment Variables

Create environment files locally and configure the variables required by your application.

Example:

```env
# Backend
DATABASE_URL=your_database_url
AI_API_KEY=your_ai_provider_api_key

# Frontend
VITE_API_BASE_URL=http://127.0.0.1:8000
```

**Note:** These variable names are examples. Use the names expected by your actual application. Never commit real API keys, database credentials, or other secrets to GitHub.

## 🔄 Development Workflow

1. Start the backend server.
2. Start the frontend development server.
3. Generate a story using the application.
4. Explore the story through interactive choices.
5. Test API endpoints using the FastAPI Swagger documentation.

## 🗺️ Future Improvements

- User authentication and story libraries
- Save and resume story progress
- Multiple genres and storytelling styles
- Improved error handling and loading states
- Deployment to cloud hosting platforms

## 👨‍💻 Author

Developed as a personal project to explore AI-powered applications, interactive storytelling, and full-stack development.
