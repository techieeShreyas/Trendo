# Trendo 🛍️

**Trendo** is a modern e-commerce platform built using **Django** and **MySQL**, designed to provide a seamless online shopping experience. The platform includes user-friendly features for both customers and administrators, focusing on scalability and real-time data management.

## Features

- **User Authentication:** Secure login and registration system with role-based access.  
- **Product Management:** CRUD operations for products with categories, prices, and stock management.  
- **Shopping Cart & Checkout:** Add items to cart, manage quantities, and complete purchases.  
- **Order Management:** Users can view order history; admins can track and manage all orders.  
- **Search & Filter:** Easily search products and filter by categories.  
- **Responsive UI:** Mobile-friendly interface using Django templates.  

## Tech Stack

- **Backend:** Django, Python  
- **Database:** MySQL  
- **Frontend:** Django Templates, HTML, CSS, JavaScript  
- **Version Control:** Git & GitHub  

## Installation

1. **Clone the repository:**  
-  git clone https://github.com/your-username/trendo.git
- Navigate to the project directory:

- cd trendo

2. **Create a virtual environment and activate it:**

- python -m venv venv
- source venv/bin/activate  # Linux/Mac
- venv\Scripts\activate     # Windows

3. **Install dependencies:**

- pip install -r requirements.txt

- Set up the database and run migrations:
 
- python manage.py makemigrations
- python manage.py migrate

4. **Run the development server:**

- python manage.py runserver

## Contribution

- Contributions are welcome! Feel free to submit issues or pull requests to improve the    project.

## License

- This project is licensed under the MIT License.