# Storhavet 

Storhavet is a full-stack e-commerce project that I am building as part of my learning in **AI for System Development and Testing**.

The name **Storhavet** is inspired by the Tamil word **Perung Kadal (பெருங்கடல்)**, meaning **“big ocean.”**

The project is being developed step by step, starting with the basic application setup and gradually adding e-commerce features and AI functionality.

## 🚀 Project Goals

The main goals of this project are to:

* Build a full-stack e-commerce application
* Practice Angular and TypeScript
* Practice ASP.NET Core and C#
* Work with databases and APIs
* Learn Git and GitHub workflows
* Integrate AI into a software development project
* Use Git commits to generate AI-assisted release notes

## 🛠️ Technology Stack

### Frontend

* Angular
* TypeScript
* HTML
* CSS
* Tailwind CSS

### Backend

* ASP.NET Core Web API
* C#
* Entity Framework Core

### Database

* PostgreSQL

### Development Tools

* Git
* GitHub
* Swagger / OpenAPI
* Docker

### AI

The project will later include an AI feature that can analyse Git commits and generate release notes.

## 📦 Planned Features

### Customer Features

* View products
* Search products
* View product details
* Add products to cart
* Update cart quantities
* Remove products from cart
* View cart total
* Checkout

### Admin Features

* Add products
* Edit products
* Delete products
* Manage product information
* View orders

### AI Feature

One of the main learning goals is to create an AI-assisted release-note generator.

For example, Git commits such as:

```text
feat: add product search
feat: add shopping cart
fix: correct cart total
fix: product image loading
```

could later be analysed by AI to generate a release-notes document such as:

```text
## Release Notes

### New Features
- Added product search
- Added shopping cart functionality

### Bug Fixes
- Fixed cart total calculation
- Fixed product image loading
```

## 📁 Project Structure

```text
Storhavet/
├── frontend/
│   └── Angular application
│
├── backend/
│   └── ASP.NET Core Web API
│
└── .gitignore
```

## ▶️ Running the Project

### Frontend

Go to the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the Angular development server:

```bash
ng serve
```

The frontend will be available at:

```text
http://localhost:4200
```

### Backend

Go to the backend folder:

```bash
cd backend
```

Run the ASP.NET Core API:

```bash
dotnet run
```

The backend runs locally on the development URL configured by ASP.NET Core.

## 📌 Current Status

The initial project setup is complete.

Current setup:

* Angular frontend created
* ASP.NET Core Web API created
* Git repository initialized
* GitHub repository connected
* Common `.gitignore` added
* Initial project setup committed and pushed

More features will be added step by step.

## 🎯 Learning Focus

This project is mainly a learning and portfolio project.

The development process will focus on understanding:

* Full-stack application architecture
* REST APIs
* Angular frontend development
* C# backend development
* Database integration
* Git workflows
* AI integration
* AI-assisted software development
* Automated release-note generation
