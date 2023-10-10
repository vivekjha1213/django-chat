# Chat360-Assignment
Task:
Make a Django channel application creating a chatroom and enabling two-way communication.




- Root Project Directory (`django-chat/`):
  - The main project directory.

- Django Project Directory (`chatweb/`):
  - The Django project directory.

- Django App Directory (`chatapp/`):
  - Directory for your Django app where you implement chat functionality.
  - Contains:
    - `__init__.py`
    - `admin.py`
    - `apps.py`
    - `consumer.py`: WebSocket consumer for chat.
    - `models.py`
    - `tests.py`
    - `views.py`
    - `migrations/`: Directory for database migartion.
    - `routing.py`: WebSocket routing for chat.

- Django Management Script (`manage.py`):
  - The Django management script for various project operations.


- ASGI Application Entry Point (`asgi.py`):
  - Entry point for ASGI (Asynchronous Server Gateway Interface) application.

- Django Settings (`settings.py`):
  - Django project settings configuration.

- URL Configuration (`urls.py`):
  - Configuration file for URL routing.

- WSGI Application Entry Point (`wsgi.py`):
  - Entry point for WSGI (Web Server Gateway Interface) application.

- Templates Directory (`template/`):
  - Directory for HTML templates (if applicable).

- Database File (`db.sqlite3`):
  - SQLite database file (or your chosen database).

- Requirements File (`requirements.txt`):
  - List of project dependencies.


  Commands:
  - Create a virtual environment: `python3 -m venv venv`
  - Activate the virtual environment:
    - On Windows: `venv\Scripts\activate`
    - On macOS and Linux: `source venv/bin/activate`
  - Install project dependencies: `pip install -r requirements.txt`
  - Start the Django development server: `python3 manage.py runserver`

- Documentation URL:
  - Django Channels Documentation: [https://channels.readthedocs.io/en/latest/installation.html]
 
![Screenshot 2023-10-10 at 9 49 06 AM](https://github.com/vivekjha1213/django-chat/assets/67068290/52f9adac-64e0-4cf9-a907-5de619cf50d5)
![Screenshot 2023-10-10 at 9 48 57 AM](https://github.com/vivekjha1213/django-chat/assets/67068290/7e7a75a3-4f2e-4673-8c04-1bf81fcda22f)
![Screenshot 2023-10-10 at 9 48 42 AM](https://github.com/vivekjha1213/django-chat/assets/67068290/7db9dbdc-f963-4fe5-b419-8cbf58e9b9db)
![Screenshot 2023-10-10 at 9 49 35 AM](https://github.com/vivekjha1213/django-chat/assets/67068290/f76ceec6-a915-4edc-8468-6d519b28d687)


