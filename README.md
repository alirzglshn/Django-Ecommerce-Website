E-Commerce Platform
A full-stack e-commerce application built with Django using server-side rendering. The project is organized into three focused Django apps — handling storefront logic, cart management, and payment/order processing — with clean separation of concerns throughout.
Tech Stack

Backend: Django (Python)
Templating: Django Templates (SSR)
Database: SQLite
Frontend: HTML, CSS, JavaScript
Tools: Django ORM, Messages Framework, Context Processors, Static and Media File Handling

Key Features

Dynamic product catalog with category filtering and search
Session-based shopping cart system
User registration and authentication
Checkout and order management workflow
Django admin panel integration
Static and media file configuration

Project Structure
AppResponsibilitycoreProducts, categories, search, authenticationcardShopping cart and session managementpaymentCheckout flow and order processing
Setup
bashgit clone https://github.com/yourusername/ecommerce-website.git
cd ecommerce-website
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
Visit http://127.0.0.1:8000/
Author
Alireza Golshan — Backend Developer (Django)
