# Complete Social Media Platform

A full-stack social media platform built using **Django**, **Django REST Framework**, and **Bootstrap**, providing core social features such as user authentication, posts, comments, likes, friends system, and real-time notifications.
This project is fully functional, deployable, and demonstrates backend, frontend, and API skills.


## Features
- User Authentication (Register, Login, Logout)
- User Profiles with bio, profile & cover pictures
- Create, Edit, and Delete Posts
- Like & Comment on Posts
- Friend Requests & Following System
- Real-time Notifications (Django Channels)
- REST API for mobile app integration
- Responsive Frontend using Bootstrap
- Search and Filtering Functionality
- Privacy Settings & Content Moderation
- Deployment-ready for cloud platforms


## Tech Stack

- **Backend:** Python, Django, Django REST Framework  
- **Frontend:** HTML, CSS, Bootstrap (Django Templates)  
- **Real-time:** Django Channels  
- **Database:** SQLite (default) / PostgreSQL (optional)  
- **Deployment:** Render / Railway / Heroku  
- **Version Control:** Git & GitHub


## Project Folder Structure

Complete-Social-Media-Platform/
│
├── manage.py
├── requirements.txt
├── .env.example
├── social_platform/ # Project configuration
│ ├── settings.py
│ ├── urls.py
│ └── asgi.py # For Channels
├── users/ # User management app
│ ├── models.py # UserProfile
│ ├── views.py
│ ├── urls.py
│ └── templates/
├── posts/ # Posts & interactions
│ ├── models.py
│ ├── views.py
│ └── templates/
├── friends/ # Friend system & following
├── notifications/ # Real-time notifications
├── api/ # REST API endpoints
├── templates/ # Base templates
├── static/ # CSS, JS, images
├── media/ # Uploaded images
└── tests/ # Test cases


## Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/<your-username>/Complete-Social-Media-Platform.git
cd Complete-Social-Media-Platform

2. Create and activate virtual environment
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Apply migrations
python manage.py migrate

5.Run development server
python manage.py runserver
Open in browser: http://127.0.0.1:8000/


## API Endpoints
- /api/posts/ → List/Create Posts
- /api/comments/ → Add Comments
- /api/likes/ → Like/Unlike Posts
- /api/friends/ → Friend Requests & Following
- /api/notifications/ → User Notifications
- Swagger documentation available at /swagger/


## Future Enhancements
- Real-time chat
- Groups & Events
- Advanced content moderation
- React frontend integration


## Author
Srija Akula
GitHub: https://github.com/Srija-Akula


## License
MIT License

