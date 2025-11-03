# 🛍️ Django E-commerce Platform

This project is a full-stack web application built with **Django**, a high-level Python web framework for building secure, maintainable, and scalable web systems.  
It provides a complete setup with modular apps for products, categories, carts, user accounts, and search functionality.

---

## 🧠 Project Overview
The **Django E-commerce Platform** enables users to browse products, add them to a shopping cart, and place orders securely.  
It includes authentication, order tracking, search features, and an admin dashboard for managing inventory and customers.

---

## 📦 Project Features
- 👤 **User Authentication:** Register, login, logout, and manage profiles  
- 🛒 **Cart System:** Add, remove, and update items in the session-based cart  
- 🏷️ **Product Catalog:** Category-wise product listing with pagination  
- 🔍 **Search Engine:** Dynamic search for products using Django ORM filters  
- 💳 **Checkout Flow:** Order confirmation and simulated payment gateway  
- 🧾 **Order Management:** Track and manage past orders  
- 🛠️ **Admin Dashboard:** Full CRUD for products, categories, and users  
- 🎨 **Frontend Templates:** Bootstrap-based responsive UI  

---

## 🧰 Tech Stack
| Category | Technologies |
|-----------|---------------|
| Language & Framework | 🐍 Python, 🕸️ Django |
| Database | 🗄️ SQLite (default), PostgreSQL (production) |
| Frontend | 🎨 HTML, CSS, Bootstrap |
| Authentication | 🔐 Django built-in auth system |
| Search | 🔎 Django ORM filters |
| Deployment | ☁️ Render / Heroku ready |

---

## 🚀 Getting Started (Local Setup)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Software-Engineering-Projects.git
cd Ecommerce_Project

2️⃣ Create Virtual Environment
python3 -m venv venv
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Apply Migrations
python manage.py migrate

5️⃣ Run Development Server
python manage.py runserver

6️⃣ Access the App
# Open your browser and visit:
http://127.0.0.1:8000/

Ecommerce_Project/
│
├── accounts/          # User authentication and profile management
├── cart/              # Session-based cart handling
├── category/          # Product categorization
├── ecommerceproject/  # Core Django settings and URLs
├── product/           # Product models, views, templates
├── search_app/        # Product search functionality
├── shop/              # Storefront and homepage
├── static/            # CSS, JS, and image assets
├── templates/         # HTML templates
├── manage.py          # Django management commands
└── requirements.txt   # Python dependencies

☁️ Deployment

This project can be deployed easily on Render, Heroku, or PythonAnywhere:
# 1️⃣ Push your code to GitHub
git add .
git commit -m "Initial deployment setup"
git push origin main

# 2️⃣ Add environment variables (SECRET_KEY, DEBUG=False)
# 3️⃣ Connect repo to Render/Heroku and deploy 🚀

📜 License

This project is licensed under the MIT License.
Feel free to modify and use it for your learning or production needs.

💡 Author

👩‍💻 Divyasri Kadambi
✨ Django | Python | Data | Cloud Enthusiast
