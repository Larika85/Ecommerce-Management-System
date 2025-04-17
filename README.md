# 🛒 Kadai – eCommerce Website

Welcome to **Kadai**, a fully functional eCommerce website created by **Harshini** and **Larika**. The goal of this project is to simulate a real-world online shopping platform with essential features for both users and administrators.

🔗 **Live Website**: [http://kadai.rf.gd/](http://kadai.rf.gd/)

---

## 💡 Features

- 🔐 User Registration & Login  
- 🛍️ Product Browsing & Categorization  
- 🛒 Add to Cart & Checkout System  
- 💳 Order Placement  
- 🧾 Order History  
- 📦 Admin Panel for Product Management  
- ✨ Responsive Design for all screen sizes  

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
