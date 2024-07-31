# Django eCommerce Project

## Overview

This is a fully functional eCommerce web application built with Django. It includes essential features such as product listing, shopping cart, checkout, user authentication, and more. The design is responsive and visually appealing.

## Features

- **User Authentication**: Sign up, log in, and log out functionalities.
- **Product Management**: Listing, searching, and viewing products.
- **Shopping Cart**: Add, update, and delete items from the cart with AJAX.
- **Checkout**: Proceed to checkout and place orders.
- **Responsive Design**: Mobile-friendly interface.

## Technologies Used

- **Backend**: Django, Django Rest Framework
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: SQLite (default), can be changed to PostgreSQL or MySQL
- **Other Tools**: Git, GitHub

## Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-username/django-ecommerce.git
   cd django-ecommerce
   ```

2. **Create a Virtual Environment**:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Apply Migrations**:
   ```sh
   python manage.py migrate
   ```

5. **Create a Superuser**:
   ```sh
   python manage.py createsuperuser
   ```

6. **Run the Development Server**:
   ```sh
   python manage.py runserver
   ```

7. **Access the Application**:
   Open your web browser and go to `http://127.0.0.1:8000/`

## Usage

- **Admin Panel**: Access the admin panel at `http://127.0.0.1:8000/admin/` using the superuser credentials to manage products and users.
- **Shopping**: Browse products, add them to your cart, update quantities, and proceed to checkout.

## Project Structure

```
django-ecommerce/
├── ecommerce/               # Django project directory
│   ├── settings.py          # Project settings
│   ├── urls.py              # URL configurations
│   ├── wsgi.py              # WSGI configuration
│   └── ...
├── shop/                    # Django app directory
│   ├── migrations/          # Database migrations
│   ├── models.py            # Database models
│   ├── views.py             # Application views
│   ├── urls.py              # App URL configurations
│   ├── templates/           # HTML templates
│   ├── static/              # Static files (CSS, JS, images)
│   └── ...
├── cart/                    # Cart functionality
│   ├── views.py             # Cart views
│   ├── urls.py              # Cart URL configurations
│   ├── templates/           # Cart templates
│   └── ...
├── manage.py                # Django management script
├── requirements.txt         # Project dependencies
└── README.md                # Project README file
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any features, bug fixes, or improvements.


Acknowledgements
Special thanks to my project partners, Priya and Aayushi Srivastava, for their collaboration and effort in this project. Additionally, thanks to my project guide, Dr. Satvir Singh, and the team at IKGPTU, Kapurthala, for their support and guidance. I would also like to thank my friends and family for their encouragement.

Feel free to customize this template with specific details about your project, such as the repository URL, guide's name, and any additional features or acknowledgements you wish to include.
