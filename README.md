# 🛒 E-Commerce Admin Dashboard

A modern **E-Commerce Admin Dashboard** built using **Next.js (App Router)**.  
This project provides an admin interface to manage products, orders, users, and analytics for an e-commerce platform.

🔗 Live Demo: https://e-commaerce-admin-dashboard.vercel.app/login


## 🚀 Features

- 📊 Analytics Dashboard – View sales, revenue, and performance metrics  
- 📦 Product Management – Add, update, and delete products  
- 🧾 Order Management – Track and manage customer orders  
- 👤 User Management – Handle admin and user data  
- 🎨 Reusable UI Components – Clean, modular component structure  
- ⚡ Fast & Optimized – Powered by Next.js App Router  
- 🔐 Scalable Architecture – Ready for authentication & role-based access  

---

## 🛠️ Tech Stack

- **Frontend:** Next.js 13+, React, TypeScript  
- **Styling:** Tailwind CSS  
- **Database:** Prisma ORM  
- **State Management:** React Hooks  
- **Linting:** ESLint  

---

## 📂 Project Structure

```

e_commaerce_admin_dashboard/
│
├── app/
│   ├── (auth)/
│   │   ├── login/
│   │   └── register/
│   ├── (dashboard)/
│   │   ├── analytics/
│   │   ├── orders/
│   │   ├── products/
│   │   └── users/
│   ├── api/
│   │   └── prisma/
│   ├── layout.tsx
│   └── page.tsx
│
├── components/
│   ├── ui/
│   │   ├── button.tsx
│   │   ├── badge.tsx
│   │   ├── dialog.tsx
│   │   └── table.tsx
│   ├── navbar.tsx
│   ├── sidebar.tsx
│   └── header.tsx
│
├── hooks/
│   ├── useModal.ts
│   └── useTheme.ts
│
├── lib/
│   ├── prisma.ts
│   ├── utils.ts
│   └── constants.ts
│
├── prisma/
│   ├── schema.prisma
│   └── migrations/
│
├── providers/
│   ├── theme-provider.tsx
│   └── modal-provider.tsx
│
├── public/
│   ├── images/
│   └── icons/
│
├── .gitignore
├── components.json
├── eslint.config.mjs
├── next.config.ts
├── package.json
├── package-lock.json
└── README.md

````

---

## ⚙️ Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/VishwaBhalodiya/e_commaerce_admin_dashboard.git
cd e_commaerce_admin_dashboard
````

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Run the development server

```bash
npm run dev
```

### 4️⃣ Open in browser

```
http://localhost:3000
```

---

## 🧪 Development Notes

* Pages are managed using **Next.js App Router**
* UI components are reusable and modular
* Prisma ORM is used for database interaction
* ESLint ensures clean and consistent code

---

## 🚀 Deployment

This project can be easily deployed on **Vercel**.

Steps:

1. Push the repository to GitHub
2. Import the project in Vercel
3. Deploy with default Next.js settings

Documentation:
[https://nextjs.org/docs/deployment](https://nextjs.org/docs/deployment)

---

## 👥 Contributors

* **Vishwa Bhalodiya**
* **Popat Hemangi (23IT101)**

---

## 📄 License

This project is created for **educational and learning purposes only**.

```

---

✅ **Now just:**
- Open `README.md`
- Select all
- Paste
- Commit

If you want **screenshots section**, **badges**, or **college-project formatting**, say so and I’ll update it cleanly.
```
