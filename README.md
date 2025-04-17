# 🛒 Kadai – eCommerce Website

Welcome to **Kadai**, a fully functional and responsive eCommerce website created by **Harshini** and **Larika**. Designed with simplicity and efficiency in mind, Kadai aims to provide users with a smooth online shopping experience while giving administrators full control over product listings and order management.

🔗 **Live Website**: [http://kadai.rf.gd/](http://kadai.rf.gd/)

---
## 🌟 About the Website

**Kadai** is a simulation of a real-world online store where users can browse products, view details, and place orders. The project demonstrates the integration of front-end and back-end technologies to create a dynamic and interactive website. Whether you're a shopper looking for great products or an admin managing inventory, Kadai covers all essential features of an online retail platform.

---

## 💡 Features

### 👤 User Functionality
- Account registration and secure login
- Browse products by categories
- Search functionality for quick product lookup
- Add to cart and modify quantity
- Place orders and view order history
- Responsive UI for mobile, tablet, and desktop users

### 🛠️ Admin Functionality
- Admin login with access control
- Add, update, and delete products
- View customer orders
- Manage inventory easily from the dashboard

---

## 🛠️ Tech Stack

| Technology   | Usage                     |
|--------------|---------------------------|
| HTML         | Page structure            |
| CSS          | Styling and layout        |
| JavaScript   | Client-side interactivity |
| PHP          | Server-side scripting     |
| MySQL        | Database management       |

---

## ⚙️ Installation & Setup

To run the project locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/kadai.git
   
2. **Move the Project Folder**
   - Place the project inside your web server directory (e.g., `htdocs` for XAMPP).

3. **Import the Database**
   - Open `phpMyAdmin`
   - Create a new database (e.g., `kadai_db`)
   - Import the SQL file from the `database/` folder (e.g., `kadai.sql`)

4. **Configure Database Connection**
   - Open the `config.php` file (or equivalent)
   - Update the following variables with your local server details:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "kadai_db";
     ```

5. **Run the Project**
   - Start Apache and MySQL via XAMPP or similar
   - Navigate to `http://localhost/kadai` in your browser

---

## 📂 Project Structure

```
kadai/
│
├── assets/              # CSS, JS, images
├── admin/               # Admin panel files
├── includes/            # Reusable PHP components
├── database/            # SQL file for setting up DB
├── config.php           # Database connection setup
├── index.php            # Home page
├── product.php          # Product detail view
└── ... (other core pages)
```

---

This project is built for academic and learning purposes.

---

## 📬 Contact

For feedback or questions, feel free to reach out via our website:  
🌐 [http://kadai.rf.gd/](http://kadai.rf.gd/)
