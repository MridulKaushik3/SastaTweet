# 🛠️ Django REST Practice
A personal sandbox for exploring web development with Django and the Django REST Framework (DRF). This repo is a collection of experimental features, API design patterns, and real-world backend development exercises.
🚀 Features
- 🧱 Django project setup with reusable apps
- ⚙️ Django REST Framework for building RESTful APIs
- 🔐 Authentication & permissions (Token, Session, JWT ready)
- 📦 Sample APIs for blog, user management, and more
- 🧪 Unit & integration tests for API endpoints
- 🗂️ Modular structure following best practices
📁 Project Structure
django_rest_practice/
├── core/             # Custom user model & authentication logic
├── blog/             # Sample blog app with API endpoints
├── api/              # Centralized API routing
├── tests/            # DRF tests
├── manage.py
└── requirements.txt


🧰 Getting Started
- Clone the repo
git clone https://github.com/your-username/django-rest-practice.git
cd django-rest-practice
- Set up a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
- Install dependencies
pip install -r requirements.txt
- Run migrations & start the server
python manage.py migrate
python manage.py runserver


📌 To-Do
- [ ] Add Swagger/OpenAPI schema docs
- [ ] Dockerize the setup
- [ ] Rate-limiting middleware
- [ ] Postgres support with custom configurations
🧠 Learning Goals
This project helps reinforce:
- Django project/app architecture
- REST API best practices
- Secure user authentication & session management
- Serializers, ViewSets, and Routers
- Versioning and documentation
📝 License
MIT License. Feel free to use, learn, and build upon it!

If you'd like, I can help you generate badges, create sample API docs, or even integrate it with Swagger or Postman collections. Just say the word.
