<p align="center">
  <h1 align="center">ProxNet BD — Web Application</h1>
  <p align="center">
    <strong>Designed, Developed & Maintained by ProxNet BD</strong><br>
    Powered by the <a href="https://laravel.com" target="_blank">Laravel Framework</a>
  </p>
</p>

<p align="center">
  <a href="http://tomal-ict.com/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-tomal--ict.com-blue?style=flat-square" alt="Portfolio Website"></a>
  <a href="https://github.com/tomal-ict" target="_blank"><img src="https://img.shields.io/badge/GitHub-tomal--ict-181717?style=flat-square&logo=github" alt="GitHub Profile"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License"></a>
  <img src="https://img.shields.io/badge/Developed%20by-ProxNet%20BD-orange?style=flat-square" alt="Maintained by ProxNet BD">
</p>

---

## 📌 About The Project

This web application is customized, developed, and managed by **ProxNet BD**. The system is built on the modern **Laravel** framework, designed to provide high performance, clean MVC architecture, robust security, and seamless maintainability.

### Key Highlights
- **Framework:** Laravel (PHP)
- **Architecture:** Model-View-Controller (MVC)
- **Database Engine:** MySQL / MariaDB
- **Database Backup:** Pre-packaged ready SQL dump included in `/db`
- **Security:** Built-in authentication, CSRF token protection, and input sanitization

---

## 👤 Developer & Management Profile

This project is actively operated, led, and maintained by:

- **Lead Developer & Owner:** Tomal Krishna Howlader
- **Company / Enterprise:** **ProxNet BD**
- **Official Website / Portfolio:** [http://tomal-ict.com/](http://tomal-ict.com/)
- **GitHub Profile:** [github.com/tomal-ict](https://github.com/tomal-ict)
- **YouTube Channel:** [@Tomal-IT](https://www.youtube.com/@Tomal-IT)
- **Official Email:** [info@prox.net.bd](mailto:info@prox.net.bd)
- **Direct Helpline / Phone:** `+880 1720-331586, 01705385853`
- **Address / Office:** Shamoly, Dhaka-1212, Bangladesh

---

## 🚀 Getting Started & Local Setup

Follow these simple steps to get the project up and running on your local machine:

### 1. Requirements
Ensure your local environment meets the following requirements:
- PHP >= 8.2 (with OpenSSL, PDO, Mbstring, Tokenizer, XML, and Ctype extensions enabled)
- Composer
- MySQL / MariaDB Server
- Node.js & NPM

### 2. Installation Steps

#### Step 1: Clone or Copy the Repository
```bash
git clone <repository-url>
cd <project-folder>
```

#### Step 2: Install Dependencies
```bash
# Install PHP packages
composer install

# Install Frontend assets
npm install
npm run build
```

#### Step 3: Configure Environment File
```bash
cp .env.example .env
php artisan key:generate
```

#### Step 4: Configure Database Connection
Open your `.env` file and update your MySQL database credentials:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```

#### Step 5: Import Database from the `/db` Directory
Inside the root folder of this project, you will find a **`db/`** directory containing the pre-configured SQL database dump.

1. Create a blank database in your MySQL server matching `DB_DATABASE` (e.g., via phpMyAdmin, HeidiSQL, or MySQL CLI).
2. Import the `.sql` file located in the `/db` directory:
   - **Via Command Line:**
     ```bash
     mysql -u your_database_user -p your_database_name < db/database_file.sql
     ```
     *(Note: Replace `database_file.sql` with your exact file name inside the `db/` folder)*
   - **Via phpMyAdmin / HeidiSQL:**
     Select your newly created database, go to the **Import** tab, browse the `.sql` file inside the `db/` directory, and click **Go/Import**.

*(Note: If you ever need fresh tables directly from migrations, you can instead run `php artisan migrate --seed`)*

#### Step 6: Launch the Application
```bash
php artisan serve
```
Open your browser and navigate to:
```
http://127.0.0.1:8000
```

---

## 🛠 Support & Contact Information

যেকোনো প্রকার কারিগরি সহায়তা, বাগ রিপোর্ট, সফটওয়্যার কাস্টমাইজেশন অথবা প্রজেক্ট সংক্রান্ত সাহায্যের জন্য নিচের ঠিকানায় যোগাযোগ করুন:

- 🌐 **Website:** [http://tomal-ict.com/](http://tomal-ict.com/)
- 📱 **Helpline:** `+880 1728-327173`
- ✉️ **Email:** info@prox.net.bd
- 🏢 **Organization:** ProxNet BD
- 📍 **Location:** Dhaka, Bangladesh

---

## 🔒 Security Vulnerabilities

If you discover any security issues, please report them directly to **Tomal Krishna Howlader** via email at **info@prox.net.bd** or contact through the direct helpline. All reports will be handled with high confidentiality and priority.

---

## 📄 License

This application is proprietary software developed and maintained by **ProxNet BD**. The core Laravel framework is open-sourced under the [MIT License](https://opensource.org/licenses/MIT).