# Multi-Tenant ERP System (Laravel 12)

A full-featured, multi-tenant ERP system built with Laravel 12, featuring advanced concepts like Livewire, Inertia.js, Vue.js integration, Laravel Octane, service container patterns, custom roles & permissions, and more.

---

## 🚀 Features

- 🌐 **Multi-Tenancy** with separate databases for each tenant
- 🔐 **User Roles & Permissions** using Laravel Permission package
- 🧾 **Inventory, Sales, CRM, and HR Modules**
- ⚙️ **Livewire + Alpine.js** for reactive admin UI
- 🧩 **Inertia.js + Vue 3 Integration** for hybrid SPA experience
- 🚅 **Laravel Octane** for ultra-fast performance
- 🔄 **Dynamic Form Builder** for ERP customization
- 📊 **Reports & Charts** using Chart.js or Livewire Charts
- 🔍 **Advanced Filtering & Search** across modules
- 🗃️ **Database Backups & Tenant Isolation**

---

## 🛠️ Technologies Used

- **Backend:** Laravel 12, Eloquent, Octane, Service Container, Repositories
- **Frontend:** Livewire, Inertia.js, Vue 3, Tailwind CSS
- **Auth:** Laravel Breeze / Jetstream / Fortify
- **Database:** MySQL + Laravel Migrations
- **Others:** Laravel Sanctum, Queue Workers, Cron Jobs

---

## 📁 Project Setup

### Clone the Repo
```bash
git clone https://github.com/Aaqil995/multi-tenant-erp-system.git
cd multi-tenant-erp-system

composer install
npm install && npm run dev

cp .env.example .env
php artisan key:generate

php artisan migrate --path=database/migrations/central
php artisan tenants:migrate

php artisan serve


## 🎯 Learning Goals

- Master advanced Laravel concepts like:
  - Multi-tenancy
  - Service Container & Facades
  - Laravel Octane
  - Livewire, Inertia.js, and Vue.js integration
- Apply OOP, MVC, and SOLID principles in a real project
- Improve system design, project architecture, and code quality
- Practice Laravel best practices for production-grade apps


## 📝 License

This project is open-source and available under the [MIT License](LICENSE).


## 👨‍💻 Author

**Muhammad Aaqil**

- GitHub: [@Aaqil995](https://github.com/Aaqil995)
- Email: muhammadaaqil995@gmail.com
