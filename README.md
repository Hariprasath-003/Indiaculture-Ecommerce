# 🛍️ IndiaCulture — E-commerce Website

A fully responsive e-commerce platform built using Django, designed to showcase and sell traditional Indian products. Includes cart functionality, secure checkout, order tracking, and an admin dashboard — all live at:

🌐 **Live Site:** [https://indiaculture.store](https://indiaculture.store)

---

## 🧩 Overview

**IndiaCulture** is an e-commerce web application that offers a smooth and user-friendly experience for browsing, purchasing, and managing Indian-themed products. It includes all core features needed for a production-grade online store.

---

## 🚀 Features

- 🛒 Product listing with category and price filters
- 👤 User registration and login
- 💼 Shopping cart with add/remove functionality
- 💳 Checkout system with **Razorpay** payment gateway
- 📦 Order tracking and status updates
- 🔔 Email notifications on order placement
- ⭐ Product reviews and ratings
- 🛠️ Admin dashboard for managing products, categories, orders, and customers
- 📱 Mobile-responsive UI using **Bootstrap**

---

## 🛠️ Tech Stack

| Layer      | Technology                          |
|------------|-------------------------------------|
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Backend**  | Django (Python)                  |
| **Database** | MySQL                            |
| **Payment**  | Razorpay API                     |
| **Email**    | SMTP (Django Email Backend)      |
| **Deployment** | Hosted on [https://indiaculture.store](https://indiaculture.store)

---

## 📥 Setup & Installation (Local)

### 1. Clone the repository
```bash
git clone https://github.com/Hariprasath-003/Indiaculture-Ecommerce.git
cd Indiaculture-Ecommerce
```

### 2. Create virtual environment and install dependencies
```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

### 3. Configure environment variables (e.g. `Razorpay`, `email`, etc.)
Create a `.env` file and add:
```env
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
EMAIL_HOST_USER=your_email
EMAIL_HOST_PASSWORD=your_password
```

### 4. Apply migrations
```bash
python manage.py migrate
```

### 5. Create a superuser
```bash
python manage.py createsuperuser
```

### 6. Run the development server
```bash
python manage.py runserver
```

Open your browser at `http://127.0.0.1:8000/`

---

## 🛍️ Admin Panel

- Visit: `http://127.0.0.1:8000/admin/`
- Use superuser credentials created earlier to log in
- Manage: Products, Orders, Customers, and Categories

---

## 🧑‍💻 Author

**Hariprasath L**  
Freelance Full‑Stack Developer  
[GitHub](https://github.com/Hariprasath-003) | [LinkedIn](https://linkedin.com/in/hariprasath-l-174b54270)

---

## 📄 License

This project is licensed under the MIT License.
