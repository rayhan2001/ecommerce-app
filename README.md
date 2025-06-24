# 🛒 Ecommerce App (SSO Provider)
This is the main authentication provider for the Multi-System Login demo project. When a user logs into this system, they are automatically logged into the `foodpanda-app` via a secure token-based Single Sign-On (SSO) mechanism.

## 📦 Tech Stack

- Laravel 12
- Laravel Breeze (Blade)
- Bootstrap 5
- Crypt-based token for secure SSO
- Laravel Auth (session-based)

## 🚀 Features

- Login with email & password
- Secure encrypted token generation for SSO
- Auto redirect to Foodpanda App with token
- Logout from both apps at once

## 🔧 Installation

```bash
git clone https://github.com/rayhan2001/ecommerce-app.git
cd ecommerce-app
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install && npm run dev
