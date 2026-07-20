<div align="center">

# Stockify

### Modern Inventory & Point of Sale System

A full-featured inventory and POS platform built with Ruby on Rails, designed for small and medium-sized businesses.

<p>

![Ruby](https://img.shields.io/badge/Ruby-3.4-CC342D?style=for-the-badge&logo=ruby)
![Rails](https://img.shields.io/badge/Rails-8.0-D30001?style=for-the-badge&logo=rubyonrails)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss)
![Turbo](https://img.shields.io/badge/Hotwire-Turbo-FF5A5F?style=for-the-badge)
![Stimulus](https://img.shields.io/badge/Stimulus-JS-77E8B9?style=for-the-badge)

</p>

</div>

---

# 📖 About Stockify

Stockify is a modern inventory management and point-of-sale (POS) platform built with Ruby on Rails.

It enables businesses to manage inventory, products, suppliers, sales, users, and business accounts from a single application.

The project follows Rails best practices using Service Objects, Pundit authorization, Hotwire, and AWS S3 for cloud storage.

---

# ✨ Features

## Inventory

- Product Management
- Suppliers
- Categories
- Brands
- Stock Control
- Barcode Support (Coming Soon)
- Product Images
- Catalogs

---

## Sales

- Shopping Cart
- Point of Sale
- Sales History
- Automatic Stock Updates

---

## Administration

- Multi-business Accounts
- User Management
- Roles & Permissions
- Dashboard
- Supplier Management

---

## Security

- Google OAuth Authentication
- Authorization with Pundit
- CSRF Protection
- Secure Sessions

---

# 📸 Screenshots

## Dashboard
The Dashboard Module provides a real-time overview of business performance 
by displaying key metrics such as total sales, monthly sales, top-selling products, 
revenue trends, and growth analytics, helping users monitor inventory activity
and make data-driven decisions.

![Dashboard](docs/screenshots/dashboard.png)

---

## Products
The Products Module provides complete inventory management, 
allowing users to create, update, search, and organize products. It includes supplier assignment, image uploads, 
stock management, barcode support, vehicle compatibility, advanced filtering, 
search suggestions, and direct product sales.

![Products](docs/screenshots/product/products.png)
![Products](docs/screenshots/product/7.png)


---

## Suppliers
The Suppliers Module allows users to create, manage, and organize supplier information. 
Each supplier is linked to the current account, 
providing centralized contact management and secure multi-tenant data separation.

![Suppliers](docs/screenshots/supplier/6.png)
![Suppliers](docs/screenshots/supplier/4.png)

---

## Catalogs
The Catalog Module allows users to create, manage, 
and organize products into catalogs. During creation, users 
can assign products, share catalogs with other accounts, and manage 
them through an intuitive dashboard with detailed views, editing, and product tracking.

![Catalogs](docs/screenshots/Catalogs/cat1.png)
![Catalogs](docs/screenshots/Catalogs/cat2.png)


---

## Administration
The User Roles Module provides role-based access control by allowing 
administrators to assign and remove roles from users. 
It includes searchable and paginated role management, 
ensuring users have the appropriate permissions to access different areas of the system.

![Administration](docs/screenshots/administration/1.png)
![Administration](docs/screenshots/administration/2.png)

---

## Point of Sale
The Sales & Cart Module streamlines the sales process by allowing users to 
add products manually or via barcode scanning, manage cart items, 
complete purchases, generate printable receipts and PDF sales reports, and 
process refunds while automatically updating inventory.

![POS](docs/screenshots/sales/1.png)
![POS](docs/screenshots/sales/3.png)
![POS](docs/screenshots/sales/2.png)
![POS](docs/screenshots/sales/5.png)
![POS](docs/screenshots/sales/6.png)

---

# 🎥 Demo

Coming Soon

---

# 🏗️ Architecture

Stockify follows the MVC architecture enhanced with Service Objects to keep business logic outside controllers.

```
Browser
      │
      ▼
Controllers
      │
      ▼
Policies (Pundit)
      │
      ▼
Service Objects
      │
      ▼
Models
      │
      ▼
Database
```

---

# 📂 Project Structure

```
app
├── components
├── domains
├── controllers
├── helpers
├── javascript
├── jobs
├── models
├── policies
├── services
├── views
├── spec
└── mailers
```

---

# 🛠️ Tech Stack

## Backend

- Ruby 3.4
- Ruby on Rails 8
- PostgreSQL
- Active Storage
- AWS S3
- Devise
- OmniAuth
- Pundit
- Sidekiq
- Active Job
- quaggajs

---

## Frontend

- TailwindCSS
- Hotwire
- Turbo
- Stimulus
- ViewComponent

---

## Testing

- RSpec
- FactoryBot
- Shoulda Matchers

---

# 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/Lopfel/stockify.git
```

Go to the project

```bash
cd stockify
```

Install dependencies

```bash
bundle install
```

Create database

```bash
bin/rails db:create
bin/rails db:migrate
bin/rails db:seed
```

Run the application

```bash
bin/dev
```

Open your browser

```
http://localhost:3000
```

---

# 🧪 Running Tests

```bash
bundle exec rspec
```

Run RuboCop

```bash
bundle exec rubocop
```

---

# 📈 Roadmap

- ✅ Product Management
- ✅ Supplier Management
- ✅ Inventory
- ✅ Shopping Cart
- ✅ Sales
- ✅ Dashboard
- ✅ Google Authentication
- ✅ Multi-user Accounts
- ✅ AWS S3 Storage
- 🚧 Barcode Scanner
- 🚧 Reports
- 🚧 REST API
- 🚧 Mobile App

---

# 📊 Future Improvements

- Export reports to Excel

- Email notifications

- Purchase orders

- Inventory alerts

- Analytics dashboard

- API documentation

---

# 👨‍💻 Author

## Kinverly Felix Lopez

Ruby on Rails Developer

GitHub

https://github.com/Lopfel

LinkedIn

(Add your LinkedIn)

---

# 📄 License

MIT License
