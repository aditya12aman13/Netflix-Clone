# Netflix Clone

A Netflix clone built with Django.

## Features

- User Authentication (Login, Signup)
- Movie Management (Add, Delete)
- Responsive Design

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/aditya12aman13/Netflix-Clone.git
   cd Netflix-Clone
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. Install requirements:
   *(Ensure you install Django and other necessary packages if there's a requirements.txt, else just run `pip install django`)*
   ```bash
   pip install django
   ```

4. Run database migrations:
   ```bash
   python manage.py migrate
   ```

5. Start the development server:
   ```bash
   python manage.py runserver
   ```

6. Open your browser and navigate to `http://127.0.0.1:8000/`.
