# Laravel News Admin

A **News Management System** built with **Laravel**, designed to provide an admin interface for creating, editing, publishing, and managing news articles, categories, tags, and users.  

This project can serve as a **starter admin panel** for a news portal or blogging system.

---

## 🚀 Features

- **Authentication & Authorization**
  - Admin login & registration
  - Role-based access control (Admin, Editor, User)

- **News Management**
  - Create, edit, delete, and publish news articles
  - Drafts and published state support
  - Rich text editor support for article content
  - Upload & manage images for news posts

- **Category & Tag Management**
  - Create & manage categories
  - Tagging system for articles
  - Assign multiple tags to a single news article

- **User Management**
  - Manage admin/editor accounts
  - Assign roles & permissions

- **Dashboard**
  - Overview of total posts, users, categories, and tags
  - Recent news and activity log

- **Search & Filters**
  - Search news by title or content
  - Filter news by category, tag, or author

- **Other Features**
  - Pagination & sorting
  - Responsive admin UI
  - API endpoints for integration with frontend/mobile apps

---

## 🛠️ Tech Stack

- **Framework**: Laravel 10+
- **Database**: MySQL / MariaDB
- **Frontend**: Blade, Bootstrap 5, Jquery Ajax
- **Authentication**: Custom Auth
- **Image Handling**: Laravel Filesystem & Intervention/Image
- **Optional**: REST API with Laravel Sanctum / Passport

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/laravel-news-admin.git
cd laravel-news-admin

composer install
npm install && npm run dev

cp .env.example .env

php artisan key:generate


DB_DATABASE=laravel_news_admin
DB_USERNAME=root
DB_PASSWORD=

```

##### php artisan serve

##### http://127.0.0.1:8000
