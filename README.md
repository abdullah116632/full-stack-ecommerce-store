# 🛍️ Full Stack E-commerce Store

## 📌 Overview
This is a **full-stack e-commerce web application** built with **Next.js** for both the frontend and backend. It features a **fully functional Stripe payment system**, a **PostgreSQL database**, and **Prisma ORM** for database management. The project is developed using **TypeScript** for better type safety and maintainability. The UI is styled with **Tailwind CSS** for a modern and responsive design.

## 🎯 Features
- 🛒 **Complete E-commerce Functionality** (Product Listings, Cart, Checkout)
- 💳 **Secure Payment Integration with Stripe**
- 🗄️ **PostgreSQL Database with Prisma ORM**
- ⚡ **Full-Stack with Next.js API Routes**
- 🛠️ **Developed with TypeScript for Type Safety**
- 🎨 **Modern UI with Tailwind CSS**
- 🔄 **State Management (if applicable)**
- 📦 **Optimized for Performance & SEO**

## 🛠️ Technologies Used
- **Next.js** (Full-stack React framework)
- **TypeScript** (For static typing and better code maintainability)
- **Stripe** (For payment processing)
- **PostgreSQL** (Relational database)
- **Prisma ORM** (For database operations)
- **Tailwind CSS** (For styling)
- **Next.js API Routes** (For backend functionality)
- **Fetch API** (For API requests)

## 🖼️ Screenshots
### 🏪 Homepage  
![Homepage Screenshot](https://res.cloudinary.com/dp0zdj77w/image/upload/v1742316553/forReadme/Screenshot_2025-03-18_224649_u1ngld.png)

### 💳 Checkout Page  
![Checkout Screenshot](https://res.cloudinary.com/dp0zdj77w/image/upload/v1742316562/forReadme/Screenshot_2025-03-18_224751_zbrwqo.png)

## 🔑 Environment Variables
To run this project locally, create a `.env` file in the root directory and add the following environment variables:

```
# Database Configuration
DATABASE_URL=your_sql_database_url

# Admin Credentials
ADMIN_USERNAME=admin
ADMIN_HASHED_PASSWORD=your_hashed_password

# Stripe Payment Keys
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=your_stripe_public_key

# Email Service (Resend)
RESEND_API_KEY=your_resend_api_key
SENDER_EMAIL=your_sender_email

# Server Configuration
NEXT_PUBLIC_SERVER_URL=http://localhost:3000
```


## 🚀 How to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/abdullah116632/full-stack-ecommerce-store.git
   ```
2. Navigate to the project folder:
   ```sh
   cd full-stack-ecommerce-store
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Set up PostgreSQL and configure the `.env` file:


5. Run Prisma migrations:
   ```sh
   npx prisma migrate dev
   ```
6. Start the development server:
   ```sh
   npm run dev
   ```
7. Open `http://localhost:3000/` in your browser.

## 🔥 Stripe Test Cards
Use the following test card details during checkout:
- **Card Number**: `4242 4242 4242 4242`
- **Expiry Date**: Any future date
- **CVC**: Any 3-digit number
- **ZIP Code**: Any valid ZIP

For more test card numbers, check Stripe's [official documentation](https://stripe.com/docs/testing).

## 📌 Future Improvements
- 🚀 **Implement user authentication for personalized shopping**
- 📊 **Enhance admin dashboard for order & product management**
- 📦 **Add inventory management system**
- 🌍 **Implement internationalization (i18n) for multiple languages**

## 📜 License
This project is open-source and can be modified for learning purposes.
