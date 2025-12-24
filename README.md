# Bg-Tracking 💸

Bg-Tracking is a lightweight budget planner application built with **Nuxt 3**, **Supabase**, and **Tailwind CSS**.  
It helps track income, expenses, budgets, and transaction history with a clean, modern UI.

## ✨ Features

- Single Page Application (CSR)
- Progressive Web App (PWA) support
- Supabase Authentication (Email)
- Supabase PostgreSQL database
- Add, edit, and delete transactions
- Monthly financial summary dashboard
- Budget limits per category
- Transaction history with date filtering
- Smooth loading indicators
- Custom reusable UI components

---

## 🛠 Tech Stack

- **Nuxt 3**
- **Supabase**
- **Tailwind CSS**
- **PWA**

---

## ⚙️ Setup Guide

### 1. Create Supabase Project

Create a project at https://supabase.com

### 2. Create Database Tables

Use **SQL Editor** in Supabase and run the required SQL schema  
(see `/docs/schema.sql` or project documentation).

### 3. Enable Row Level Security (RLS)

Enable RLS and apply policies to protect user data.

### 4. Environment Variables

Create a `.env` file in the root directory:

```env
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_anon_key
```

````

---

## 📦 Install Dependencies

```bash
yarn install
```

---

## 🚀 Development

```bash
yarn dev
```

---

## 🏗 Production Build

```bash
yarn generate
```

Deploy the generated `.output/public` folder to platforms like **Vercel**, **Netlify**, or any static hosting.

---

## 💱 Change Currency

Update the currency symbol from:

```ts
utils / currency.ts;
```

Modify the symbol inside `convertToCurrency()`.

---

## 📄 License

This project is for personal and educational use.

````
