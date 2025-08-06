# 🌟 Online Charity Platform

An online web-based platform designed to connect donors with individuals in need by allowing users to submit donation requests and enabling others to donate directly. The platform aims to support causes like education, healthcare, and emergency relief.

---

## 🚀 Features

- 🔐 User Registration and Login (Donor & Beneficiary roles)
- 📄 Submit and View Donation Requests
- 💳 Secure Donation Module
- 🧑‍💼 Admin Panel for Request Moderation
- 📊 Track Donations and Generate Reports
- 📱 Responsive UI for all devices

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP (Core PHP or Laravel – depending on your stack)
- **Database**: MySQL
- **Authentication**: PHP Sessions
- **Other Tools**: VS Code, XAMPP/WAMP

---

## 📸 Screenshots

> Add screenshots here if available  
> You can use:  
> ![Component UI](https://github.com/SakshiSapike/Online-Charity-Platform/blob/main/Asset/aboutus.png)
> ![Component UI](https://github.com/SakshiSapike/Online-Charity-Platform/blob/main/Asset/admin.png)
> ![Component UI](https://github.com/SakshiSapike/Online-Charity-Platform/blob/main/Asset/contactus.png)
 > ![Component UI](https://github.com/SakshiSapike/Online-Charity-Platform/blob/main/Asset/detaildata.png)
> ![Component UI](https://github.com/SakshiSapike/Online-Charity-Platform/blob/main/Asset/news.png)
> ![Component UI](https://github.com/SakshiSapike/Online-Charity-Platform/blob/main/Asset/hp.png)
  
> `![Admin Panel](screenshots/admin.png)`

---

## 📂 Project Structure
- online-charity-platform/
- │
- ├── index.php                     # Landing page (home)
- ├── login.php                     # User login page
- ├── register.php                  # User registration page
- ├── logout.php                    # Logout script
- ├── db_connect.php                # Database connection file
- │
- ├── /dashboard/                   # Dashboards for different users
- │   ├── donor_dashboard.php
- │   ├── beneficiary_dashboard.php
- │   └── admin_dashboard.php
- │
- ├── /requests/                    # Donation request handling
- │   ├── submit_request.php
- │   ├── view_requests.php
- │   ├── approve_request.php       # Admin approval script
- │   └── delete_request.php
- │
- ├── /donations/                   # Donation-related actions
- │   ├── donate.php
- │   └── donation_history.php
- │
- ├── /admin/                       # Admin-specific functions
- │   ├── manage_users.php
- │   ├── view_reports.php
- │   └── site_settings.php
- │
- ├── /includes/                    # Reusable components
- │   ├── header.php
- │   ├── footer.php
- │   └── nav.php
- │
- ├── /assets/                      # Static resources
- │   ├── /css/
- │   │   └── style.css
- │   ├── /js/
- │   │   └── script.js
- │   └── /images/
- │       └── logo.png
- │
- ├── /screenshots/                 # Screenshots for README
- │   ├── home.png
- │   └── dashboard.png
- │
- └── README.md                     # Project documentation

