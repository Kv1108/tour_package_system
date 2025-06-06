# 🧳 Tour Package Management System

A full-featured Django web application designed to manage travel and tour packages, built with a focus on usability, transparency, and secure transactions. It supports three types of users: **Customer**, **Vendor**, and **Admin**, each with their own powerful dashboard and feature set.

---

## 🔑 Features

### 👤 Customer
- 🔍 Explore and book travel packages
- 🧭 Itinerary management with multi-batch support
- 📈 Smart tour recommendations
- 📚 Booking history & itinerary tracking
- 💬 Real-time communication with vendors
- 🪙 Coin-based reward system
- 🤝 Secure bookings with escrow integration
- 🌐 Community discussion forums
- 🔔 Notifications & alerts

### 🧑‍💼 Vendor
- 📊 Vendor dashboard and analytics
- ✏️ Create & manage tour packages and batches
- 📡 Real-time booking tracker
- 💬 Chat & Q&A with customers
- 💸 Track earnings and payouts
- ✅ Vendor verification system
- ⭐ Manage customer reviews

### 🛡️ Admin
- 🧩 Admin dashboard
- 🧑‍🔧 User & vendor management
- ✅ Tour package & review moderation
- 💳 Escrow and payment flow control
- 📢 Broadcast notifications & emails
- 📈 Platform analytics
- 🌍 Community & forum moderation

---

## ⚙️ Tech Stack

| Layer       | Technology                         |
|-------------|-------------------------------------|
| Backend     | Django, Django REST Framework       |
| Frontend    | HTML, CSS, Bootstrap, JavaScript    |
| Database    | SQLite / PostgreSQL                 |
| Real-Time   | Django Channels                     |
| Async Tasks | Celery + Redis                      |
| Payments    | Razorpay / Stripe                   |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip
- Node.js (if using frontend build tools)
- PostgreSQL (recommended for production)

### Installation

```bash
git clone https://github.com/your-username/tour-package-system.git
cd tour-package-system

# Create virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Start server
python manage.py runserver

```


🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

📜 License
This project is licensed under the MIT License.
