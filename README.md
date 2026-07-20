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

![Dashboard](docs/screenshots/dashboard.png)

---

## Products

![Products](docs/screenshots/product/1.png)
![Products](docs/screenshots/product/2.png)
![Products](docs/screenshots/product/3.png)
![Products](docs/screenshots/product/4.png)
![Products](docs/screenshots/product/5.png)
![Products](docs/screenshots/product/6.png)
![Products](docs/screenshots/product/7.png)

![Products](docs/screenshots/product/products.png)

---

## Suppliers

![Suppliers](docs/screenshots/supplier/2.png)
![Suppliers](docs/screenshots/supplier/3.png)
![Suppliers](docs/screenshots/supplier/4.png)
![Suppliers](docs/screenshots/supplier/5.png)
![Suppliers](docs/screenshots/supplier/6.png)

---

## Catalogs

![Catalogs](docs/screenshots/Catalogs/1.png)
![Catalogs](docs/screenshots/Catalogs/2.png)
![Catalogs](docs/screenshots/Catalogs/3.png)
![Catalogs](docs/screenshots/Catalogs/4.png)


---

## Administration

![Administration](docs/screenshots/administration/1.png)
![Administration](docs/screenshots/administration/2.png)
![Administration](docs/screenshots/administration/3.png)
![Administration](docs/screenshots/administration/4.png)

---

## Point of Sale

![POS](docs/screenshots/sales/1.png)
![POS](docs/screenshots/sales/2.png)
![POS](docs/screenshots/sales/3.png)
![POS](docs/screenshots/sales/4.png)
![POS](docs/screenshots/sales/5.png)
![POS](docs/screenshots/sales/6.png)
![POS](docs/screenshots/sales/7.png)

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

# 🔑 Environment Variables

Create a `.env` file.

```text
DATABASE_URL=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_BUCKET=
AWS_REGION=
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

# 🤝 Contributing

Contributions are welcome.

Feel free to fork the repository and submit a Pull Request.

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
