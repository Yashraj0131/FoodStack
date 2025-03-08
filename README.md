# Foostack - Food Delivery Project

## Introduction
Foostack is a dynamic food delivery platform designed to provide users with a seamless browsing and ordering experience. Inspired by popular services like Swiggy and Zomato, Foostack aims to bring restaurants closer to customers with intuitive navigation, efficient search filters, and detailed food category listings.

---

## Features
- User Authentication System (Sign Up/Sign In)
- Restaurant Browsing with Filter Options
- Detailed Menu Display with Categories
- Integration of Popular Restaurant Chains like Pizza Hut and Domino's
- Dynamic Rating and Review System
- Location-based Restaurant Suggestions
- Razorpay Integration for Secure Payments

---

## Installation
Follow these steps to set up Foostack on your local machine:

1. **Clone the Repository:**
   ```bash
   git clone <repository_link>
   cd Foostack
   ```

2. **Create and Activate Virtual Environment:**
   ```bash
   python -m venv myenv
   source myenv/bin/activate  # On Windows use: .\myenv\Scripts\activate
   ```

3. **Install Required Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Migrations:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create Superuser (For Admin Access):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the Application:**
   Visit `http://localhost:8000/`

---

## Screenshots
### Homepage
![Homepage](./screenshots/Screenshot_164.png)

### Pizza Hut Menu
![Pizza Hut](./screenshots/Screenshot_165.png)

### Domino's Menu
![Domino's](./screenshots/Screenshot_166.png)

### Checkout Page
![Checkout](./screenshots/Screenshot_167.png)

### Payment Gateway (Razorpay)
![Razorpay](./screenshots/Screenshot_169.png)

### Order Confirmation
![Order Confirmation](./screenshots/Screenshot_170.png)

### User Profile and Orders
![User Profile](./screenshots/Screenshot_171.png)

### Admin Dashboard
![Admin Dashboard](./screenshots/Screenshot_172.png)

---

## Upcoming Features
- Real-Time Order Tracking
- Push Notifications for Order Status
- Integration with More Restaurant Chains
- Improved UI Design and Enhanced User Experience

---

## Contribution
We welcome contributions! If you'd like to improve Foostack, follow these steps:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/new-feature`
3. Commit changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request.

---

## License
This project is licensed under the MIT License.

---

## Contact
For queries or collaborations, feel free to reach out:
- **Email:** yashrajmishra45@gmail.com
- **GitHub:** [Yashraj0131](https://github.com/Yashraj0131)

---

**Happy Coding! 🚀**
