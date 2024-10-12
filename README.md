# Django Book Lovers Community

A dedicated social media application built with Django, designed to bring together book lovers in a single community. Users can create profiles, follow each other, post comments, and utilize hashtags to share their thoughts and recommendations on books.

## Features

- User authentication (registration, login, logout)
- Profile creation and editing
- Follow/unfollow other users
- Post creation, editing, and deletion
- Comment on posts
- Hashtags for categorizing and discovering content
- Responsive design

## Technologies Used

- Django
- Python
- HTML/CSS
- JavaScript
- SQLite (or your preferred database)

## Installation

### Prerequisites

- Python 3.x
- Django
- Git

### Clone the Repository and Set Up the Environment

```bash
git clone https://github.com/yourusername/repo.git
cd repo
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
