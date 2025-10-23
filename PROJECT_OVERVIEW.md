# 🚚 ShipSmart

**Smart shipping made simple.**  
ShipSmart is a Django-based order fulfillment and courier management system that helps online retailers generate shipping labels (PDF), track parcels, and send automated updates — all from one dashboard.

---

## 🧩 Overview

ShipSmart is designed for e-commerce businesses that need a seamless way to manage the logistics layer of their operations.  
It integrates order creation, courier APIs, PDF label generation, and automated notifications into one unified platform.

---

## ⚙️ Core Features

| Feature | Description |
|----------|-------------|
| **Order Management** | Create and manage customer orders with status tracking. |
| **Courier Integration** | Connect APIs for real-time shipment tracking. |
| **PDF Label Generator** | Generate branded shipping labels using WeasyPrint. |
| **Email Notifications** | Automatic updates on dispatch and delivery. |
| **REST API** | Secure JWT-based endpoints for integration with stores. |
| **Admin Dashboard** | Role-based tools for managing retailers and shipments. |
| **Analytics (optional)** | Delivery performance metrics and fulfillment insights. |

---

## 🏗️ Tech Stack

- **Backend:** Django 5.x  
- **Frontend:** Bootstrap 5 (custom, no SCSS)  
- **Database:** PostgreSQL  
- **APIs:** Django REST Framework + SimpleJWT  
- **Tasks:** Celery + Redis  
- **PDF Engine:** WeasyPrint  
- **Environment:** Python-dotenv  

---

## 📁 Project Structure

shipsmart/
├── accounts/          # Authentication & roles
├── orders/            # Order models and views
├── shipping/          # Courier logic & PDF labels
├── notifications/     # Email + in-app alerts
├── api/               # REST API endpoints
├── templates/         # Bootstrap templates
├── static/            # CSS, JS, images
└── shipsmart/         # Core config and settings


---

## 🧪 Key Concepts Covered

- Project configuration (dev/prod split)
- Model relationships and inheritance
- Forms and template views
- Django admin customization
- Messages, emails, and PDF reporting
- REST API design with DRF
- Testing workflows and database management

---

## 🚀 Getting Started

```bash
git clone https://github.com/V-FOR-VEND3TTA/shipsmart.git
cd shipsmart
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` to view the landing page.

---

## 🧠 Future Enhancements

* Webhooks for courier status updates
* Analytics dashboard (delivery time, cost efficiency)
* Stripe or PayPal integration for billing
* Multi-tenant SaaS model for agencies

---

**Build smarter logistics. Ship faster. Think ShipSmart.**
