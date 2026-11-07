# 🛍️ PickMart – E-Commerce Website

## 📌 About the Project

PickMart is a web-based e-commerce application developed using Python and Django. It provides an online shopping platform where users can explore products and access customer and shopping cart sections.

The project is designed with a modular Django structure, making it easier to manage products, customers, and orders.

## ✨ Project Modules

- **Products:** Product listing, product details, and product management.
- **Customers:** Customer account section.
- **Orders:** Shopping cart and order-related section.
- **Themes:** Additional application structure and customization.

## 🛠️ Technologies Used

- Python
- Django
- HTML
- CSS
- JavaScript
- SQLite

## 📂 Project Structure

```text
PickMart/
│
├── PickMart/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── customers/
├── products/
├── orders/
├── themes/
├── templates/
├── static/
├── media/
├── manage.py
└── README.md
```

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/nikhila-M-nikki/PickMart.git
```

### 2. Navigate to the project folder

```bash
cd PickMart
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install Django

```bash
pip install Django
```

Install any additional dependencies required by the project.

### 6. Apply database migrations

```bash
python manage.py migrate
```

### 7. Run the development server

```bash
python manage.py runserver
```

### 8. Open the application

Visit:

http://127.0.0.1:8000/

## 🔒 Security Notes

Before production deployment:
- Keep the Django secret key private.
- Set DEBUG to False.
- Configure ALLOWED_HOSTS.
- Use environment variables for sensitive settings.

## 👩‍💻 Author

**Nikhila M.**

## 📄 License

No license has been specified for this project yet.