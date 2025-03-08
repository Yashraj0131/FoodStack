# FoodStack - Online Food Ordering System

FoodStack is a Django-based web application that allows users to register as restaurant owners or customers. Restaurant owners can add, edit, and delete restaurants, while customers can browse menus, place orders, and make payments using Razorpay.

## Features

### **Authentication**
- User registration and login (for both restaurant owners and customers)
- Secure authentication using Django's built-in authentication system

### **Restaurant Management**
- Add new restaurants
- Edit and update restaurant details
- Delete restaurants

### **Menu & Orders**
- Customers can browse menus
- Add items to the cart
- Place orders

### **Payment Integration**
- Razorpay integrated for secure online payments

## Installation & Setup

### **1. Clone the Repository**
sh
git clone https://github.com/your-username/FoodStack.git
cd FoodStack


### **2. Set Up a Virtual Environment**
sh
python3 -m venv venv
source venv/bin/activate  # For Mac/Linux


### **3. Install Dependencies**
sh
pip install -r requirements.txt


### **4. Apply Migrations**
sh
python manage.py migrate


### **5. Create a Superuser**
sh
python manage.py createsuperuser


### **6. Run the Development Server**
sh
python manage.py runserver


Now, open your browser and go to http://127.0.0.1:8000/

## Directory Structure
FoodStack/
│── delivery/
│   │── migrations/
│   │── static/
│   │── templates/delivery/
│   │   ├── add_res.html
│   │   ├── base.html
│   │   ├── checkout.html
│   │   ├── cusmenu.html
│   │   ├── customer_home.html
│   │   ├── display_res.html
│   │   ├── failed.html
│   │   ├── index.html
│   │   ├── menu.html
│   │   ├── orders.html
│   │   ├── show_cart.html
│   │   ├── sign_in.html
│   │   ├── sign_up.html
│   │   ├── success.html
│   │   ├── userdata.html
│   │── __init__.py
│   │── admin.py
│   │── apps.py
│   │── forms.py
│   │── models.py
│   │── tests.py
│   │── views.py
│── manage.py
│── requirements.txt


## API Endpoints (If Using Django REST Framework)
| Method | Endpoint | Description |
|--------|----------------|--------------------------------|
| GET | /restaurants/ | List all restaurants |
| POST | /restaurants/add/ | Add a new restaurant |
| PUT | /restaurants/update/<id>/ | Update restaurant details |
| DELETE | /restaurants/delete/<id>/ | Delete a restaurant |
| GET | /menu/ | Get menu items |
| POST | /order/ | Place an order |

## Razorpay Payment Integration
1. Sign up at [Razorpay](https://razorpay.com/)
2. Get API keys from Razorpay Dashboard
3. Add API keys to Django settings:
python
RAZORPAY_KEY_ID = "your_key_id"
RAZORPAY_KEY_SECRET = "your_key_secret"

## Screenshots
Below are some screenshots that showcase the interface and functionality of Foostack:

Home Page

![Screenshot (165)](https://github.com/user-attachments/assets/2e2ae5ff-2ec6-491d-be36-9e17db87d99f)


Menu Listings

![Screenshot (167)](https://github.com/user-attachments/assets/443207ff-2697-4687-bd41-eadf6c309bb1)


Menu Integration

![Screenshot (166)](https://github.com/user-attachments/assets/4ea971a9-6c3d-47d3-b169-2ee52b196833)


Checkout and Payment
![Screenshot (169)](https://github.com/user-attachments/assets/2d5ebbf5-cf8a-49f4-9aad-6976c28f2c2c) 

![Screenshot (170)](https://github.com/user-attachments/assets/26e67c46-8f1b-4f53-b7ba-959c9d414e55)





## Contact
For queries or suggestions, feel free to reach out:
Email: support@foostack.com
GitHub: Foostack Repo
