# Shoply - E-Commerce Platform

## Overview
Shoply is an advanced e-commerce platform designed for seamless grocery and household shopping. It features an intuitive UI, advanced filtering options, AI-powered recommendations, and real-time order tracking to enhance the user experience.

## Authors
- **Anas Yousef Issa Alraoush**
- **Mohammad Nasser Jaber**
- **Osama Tayseer Abu Alwafa**
- **Reham Abuhadba**
- **Ghalib Dhia Albasheer**

## Supervisor
- **Prof. Rana Yousef**

## University Affiliation
- **Software Engineering Department, The University of Jordan**
- **Date: 2024**

## Features
- **User Authentication**: Secure login, registration, and third-party authentication.
- **Product Browsing & Filtering**: Users can search and filter products by category, price, and brand.
- **Personalized Recommendations**: AI-based suggestion system.
- **Shopping Cart & Checkout**: Seamless cart management and multiple payment options.
- **Order Tracking**: Real-time tracking for deliveries.
- **Admin Dashboard**: Product and inventory management.
- **Delivery Personnel Module**: Order assignments, updates, and customer interaction.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript (React/Angular)
- **Backend**: Node.js/Python (Django/Flask)
- **Database**: MySQL/PostgreSQL
- **Security**: AES-256 encryption, OWASP ZAP for penetration testing
- **Deployment**: Docker, Cloud Hosting
- **Payment Gateway**: PayPal/Stripe integration
- **AI**: Machine Learning for personalized recommendations

## Installation
### Prerequisites
- Install **Node.js** and **Python**
- Install dependencies
```bash
pip install -r requirements.txt
npm install
```

### Running the Application
```bash
# Start Backend Server
python backend/server.py

# Start Frontend
npm start
```

## Project Structure
```
Shoply/
│-- frontend/
│-- backend/
│-- database/
│-- docs/
│-- tests/
│-- README.md
```

## API Endpoints
| Method | Endpoint | Description |
|--------|--------------------|--------------------------------|
| GET | /products | Fetch all products |
| GET | /products/:id | Fetch single product details |
| POST | /cart/add | Add product to cart |
| GET | /orders/:id | Get order details |
| POST | /checkout | Process payment |

## Security Measures
- **Data Encryption**: AES-256 for sensitive user data.
- **Authentication**: Secure login with JWT.
- **Compliance**: GDPR-compliant data handling.

## Future Enhancements
- **Mobile App**: Develop a mobile application.
- **Multi-Vendor Support**: Allow multiple sellers.
- **AI Chatbot**: Provide automated customer support.

## License
This project is open-source and available for academic and research purposes.

