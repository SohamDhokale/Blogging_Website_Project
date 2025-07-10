# Blogging Website Project

A full-featured blogging platform built with Django. This project allows users to create, edit, and manage blog posts, comment on articles, and interact with a modern, responsive interface.

## Features
- User authentication (login, logout, register)
- Create, edit, and delete blog posts
- Comment on posts
- Responsive design
- Admin panel for content management
- Image upload for posts

## Getting Started

### Prerequisites
- Python 3.8+
- pip
- Virtualenv (recommended)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/SohamDhokale/Blogging_Website_Project.git
   cd Blogging_Website_Project
   ```
2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```
5. **Create a superuser (admin):**
   ```bash
   python manage.py createsuperuser
   ```
6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
7. **Access the site:**
   - Blog: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
   - Admin: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

## Technologies Used
- Python
- Django
- SQLite 
- HTML, CSS, JavaScript
- Bootstrap (for UI)

## Folder Structure
- `myapp/` - Main Django app for blog logic
- `myproject/` - Project settings and configuration
- `templates/` - HTML templates
- `static/` - Static files (CSS, JS, images)
- `media/` - Uploaded media files

## Screenshots

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE) (or specify your license)
