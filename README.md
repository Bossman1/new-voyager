# 🚀 New Voyager Admin Panel for Laravel 12

[![Laravel Version](https://img.shields.io/badge/Laravel-12.0-red.svg?style=flat-square&logo=laravel)](https://laravel.com)
[![PHP Version](https://img.shields.io/badge/PHP-8.3-777BB4.svg?style=flat-square&logo=php)](https://php.net)
[![MySQL Version](https://img.shields.io/badge/MySQL-5.7-4479A1.svg?style=flat-square&logo=mysql)](https://www.mysql.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

> A powerful and modern admin panel for Laravel 12, designed to make your development process faster and more efficient.

---

## ✨ Prerequisites

| Requirement | Version |
|------------|---------|
| Laravel    | 12.0    |
| PHP        | 8.3     |
| MySQL      | 5.7     |

---

## 📦 Installation Guide

### 🛠️ Setting Up Laravel Project

1. **Install new Laravel project**
2. **Enter project root directory and run:**
   ```bash
   composer install
   ```
3. **Configure environment:**
   - Create `.env` file
   - Configure database (MySQL recommended)

4. **Generate application key:**
   ```bash
   php artisan key:generate
   ```

5. **Create storage link:**
   ```bash
   php artisan storage:link
   ```

6. **Install and build assets:**
   ```bash
   npm install && npm run build
   ```

7. **Run migrations:**
   ```bash
   php artisan migrate
   ```

### 🎯 Installing New-Voyager Package

1. **Install the package:**
   ```bash
   composer require nick-kh/new-voyager
   ```

2. **Choose installation type:**
   ```bash
   # With dummy data
   php artisan new-voyager:install --with-dummy

   # Clean installation
   php artisan new-voyager:install
   ```

3. **Start the development server:**
   ```bash
   php artisan serve
   ```
   Then visit: [`http://localhost:8000/admin`](http://localhost:8000/admin)

4. **Default Admin Credentials** (if installed with dummy data):
   ```
   📧 Email: admin@admin.com
   🔑 Password: password
   ```

### 👥 Admin User Management

**Assign admin privileges to existing user:**
```bash
php artisan new-voyager:admin your@email.com
```

**Create new admin user:**
```bash
php artisan new-voyager:admin your@email.com --create
```

---

## 📚 Documentation

For comprehensive documentation, visit the [Official Voyager Documentation](https://voyager-docs.devdojo.com/) 📖

## 📝 License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

---

<div align="center">

**Made with ❤️ for the Laravel Community**

[Report Bug](https://github.com/Bossman1/laravelvoyager/issues) · [Request Feature](https://github.com/Bossman1/laravelvoyager/issues)

</div>