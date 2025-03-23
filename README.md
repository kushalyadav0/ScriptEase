# ScriptEase

ScriptEase is a powerful web application that enables users to create, manage, and refine scripts effortlessly. It integrates AI-powered assistance to enhance the writing process while allowing users to draft and store their scripts efficiently.

## Features

### ✅ Core Features (First Version)
- **User Authentication**: Sign up, log in, and manage your profile securely.
- **Script Creation & Management**: Write, edit, and save scripts in the dashboard.
- **AI Assistance**: Get AI-powered suggestions for scriptwriting.
- **Draft Management**: Save and retrieve previously created drafts.

### 🚀 Further Development
- **AI-generated full scripts** based on user input.
- **Google OAuth authentication** for easier login.
- **Role-based system (Admin & Users)** for organization-like workflow.
- **Advanced dashboard analytics** to track script engagement.

## Tech Stack

### 🖥 Frontend:
- HTML, CSS, TailwindCSS
- JavaScript, React

### ⚙️ Backend:
- Django (Handles AI requests & authentication)
- PostgreSQL (Database)

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/scriptease.git
cd scriptease

# Backend Setup
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

# Frontend Setup
cd ../frontend
npm install
npm start
```

## Deployment
- **Frontend**: Vercel
- **Backend**: Railway
- **Database**: Supabase (PostgreSQL)

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Feel free to fork this repo and submit a PR.

## Contact
For any queries, reach out via [LinkedIn](https://www.linkedin.com/in/kushal-yadav-799310318/).
