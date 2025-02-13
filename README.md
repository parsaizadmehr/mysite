# Django blog

This project is a simple blogging platform built using Django.

- **User Authentication**: Secure user authentication system allowing users to create, manage, and personalize their accounts.
- **Post Management**: Create, edit, and delete blog posts with ease.
- **Password Reset**: Hassle-free password reset functionality for users.
- **Comment**: Comment system.
- **Search posts by title or content**: Search functionality.

1. Clone the repository:
```
git clone https://github.com/parsaizadmehr/Django-Blog.git
```

2. Navigate to the project directory:
```
cd Django-Blog
```

3. Install dependencies:
```
pip install -r requirements.txt
```

4. Edit env.sample
```
cp .env.sample .env
```

5. Run migrations:
```
python manage.py migrate
```

6. Start the development server:
```
python manage.py runserver
```

## Usage
- Access the admin panel: `/admin` (create a superuser with `python manage.py createsuperuser`)

