# Complete Social Media Platform (Django)

A **fully‑featured social media web application** built using **Django**, **Django REST Framework**, and **modern web technologies**. This project demonstrates real‑world backend and full‑stack development concepts such as authentication, social interactions, real‑time notifications, REST APIs, and cloud deployment.


## Project Overview

The **Complete Social Media Platform** allows users to:

* Create profiles and manage personal information
* Share posts with images
* Like and comment on posts
* Send and accept friend requests
* Follow other users
* Receive real‑time notifications
* Access REST APIs for mobile or frontend integration

This project is designed to be **scalable, modular, and portfolio‑ready**.


## Features

### User Management

* User registration & login
* Profile creation with bio, profile picture & cover photo
* Secure authentication and authorization

### Posts & Interactions

* Create, edit, delete posts
* Image uploads
* Like & unlike posts
* Comment system

### Social Features

* Friend request system
* Follow / unfollow users
* Who‑to‑follow suggestions

### Notifications

* Real‑time notifications using **WebSockets (Django Channels)**
* Notifications for likes, comments & follows

### REST API

* Built using **Django REST Framework**
* Ready for mobile apps or frontend frameworks

### Frontend

* Responsive UI using **Bootstrap**
* Clean and user‑friendly design

### Advanced

* Search and filtering
* Privacy settings
* Content moderation ready


## Tech Stack

* **Backend:** Python, Django
* **API:** Django REST Framework
* **Real‑Time:** Django Channels, WebSockets
* **Frontend:** HTML, CSS, Bootstrap, JavaScript
* **Database:** SQLite / PostgreSQL
* **Media Handling:** Pillow
* **Deployment:** Render / Railway / Heroku


## Project Structure

social_media_platform/
│── manage.py
│── requirements.txt
│── docker-compose.yml
│── .env.example
│── README.md
│
├── social_media_platform/     # Project settings
├── users/                     # User & Profile management
├── posts/                     # Posts, Likes, Comments
├── friends/                   # Friends & Follow system
├── notifications/             # Notifications & WebSockets
├── api/                       # REST API
├── templates/                 # HTML templates
├── static/                    # CSS, JS, Images
├── media/                     # Uploaded files
├── tests/                     # Test cases
└── docs/                      # Documentation


## Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/Srija-Akula/Complete-Social-Media-Platform.git
cd Complete-Social-Media-Platform
```

### Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Environment Variables

Create a `.env` file using `.env.example`

```env
SECRET_KEY=your-secret-key
DEBUG=True
DATABASE_URL=sqlite:///db.sqlite3
```

### Database Migration

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run the Server

```bash
python manage.py runserver
```

Open: **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**


## Testing

```bash
python manage.py test
```


## Deployment

The project is deployment‑ready for:

* **Render**
* **Railway**
* **Heroku**

Refer to `docs/deployment.md` for detailed steps.


## swagger documentation
from drf_yasg.views import get_schema_view


## Sample Output

* User feed with posts
* Likes & comments
* Real‑time notifications
* Profile statistics


## Future Enhancements

* Real‑time chat system
* Groups & events
* Stories feature
* Dark mode
* Advanced content moderation


## License

This project is licensed under the **MIT License**.


## Author

 Srija Akula
GitHub: https://github.com/Srija-Akula



