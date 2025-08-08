# Ignite SACCO Platform 💰🔥

**Ignite SACCO** is a web-based savings and loan management platform designed for small groups and Chamas in Kenya. It enables members to pay monthly savings, request and repay loans, and receive automated reminders via WhatsApp. Admins manage members, view reports, and track all transactions.

---

## 🌟 Features

### 🔒 Authentication
- Role-based login system (Admin / User)
- Secure login using unique credentials
- Automatic redirection to dashboards based on role

### 👤 User Dashboard
- Pay monthly savings via **M-Pesa STK Push**
- View and download **payment history**
- Request and pay back **loans**
- View **loan eligibility criteria**
- Manage personal **profile**, including picture and password updates

### 🛠️ Admin Dashboard
- Add and manage members
- View payment and loan reports
- Send **automated WhatsApp reminders** for due savings or loans
- Manage users and complaints
- Export data as PDF

---

## 💻 Tech Stack

| Technology      | Purpose                     |
|-----------------|-----------------------------|
| **HTML**        | Markup structure            |
| **Tailwind CSS**| Responsive styling          |
| **JavaScript**  | Frontend interactivity      |
| **Node.js + Express** | Backend server/API |
| **MySQL**       | Relational database         |
| **M-Pesa Daraja API** | STK Push payments    |
| **Twilio or WhatsApp API** | Notifications |
| **AOS.js**      | Dashboard animations        |

---

## 🧭 Project Structure

```bash
IgniteSacco/
│
├── backend/                     # Express backend
│   ├── routes/                  # API routes
│   ├── controllers/             # Controller logic
│   ├── models/                  # MySQL queries
│   └── config/                  # DB and API setup
│
├── public/                      # Static assets
│   ├── css/                     # Tailwind CSS files
│   └── js/                      # JavaScript logic
│
├── views/                       # HTML pages
│   ├── login.html
│   ├── admin-dashboard.html
│   ├── user-dashboard.html
│   ├── profile.html
│   ├── request-loan.html
│   ├── pay-loan.html
│   ├── payment-history.html
│   └── loan-eligibility.html
│
└── README.md                    # Project documentation
