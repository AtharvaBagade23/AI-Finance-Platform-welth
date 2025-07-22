
# Welth – AI-Powered Personal Finance Platform 💸🤖

An advanced full-stack finance management platform built with **Next.js 15**, **React 19**, **Tailwind CSS**, and powerful integrations like **Supabase**, **Prisma**, **Clerk Authentication**, **Inngest**, and **Arcjet**. Welth helps users securely manage their accounts, track expenses, analyze financial patterns, and receive AI-driven insights.

---

## 🔑 Features

- 🔐 **Clerk Authentication** – Secure login/signup
- 📊 **Dashboard & Expense Analytics** – Charts, filters, visual reports
- 🧾 **AI-Powered Receipt Scanner (OCR)** – Extract and log transactions from uploaded receipts
- 💼 **Multiple Account Support** – Create, switch, and manage multiple bank accounts
- 🗂 **Transaction Management** – View, add, edit, delete, and bulk-manage transactions
- 📅 **Budget Alerts & Recurring Jobs** – Set monthly budgets, get notified with Inngest cron jobs
- 📧 **Monthly Reports** – Automated AI-generated insights emailed to users
- 🔐 **Arcjet Shield** – Rate limiting and bot protection
- 🌐 **Deployed on Vercel** for lightning-fast performance

---

## 🛠 Tech Stack

| Layer       | Tools Used                                           |
|------------|------------------------------------------------------|
| Frontend   | React 19, Next.js 15, Tailwind CSS, Shadcn UI        |
| Backend    | Supabase, Prisma ORM, Inngest (Serverless Functions) |
| Auth       | Clerk                                                |
| Dev Tools  | Postman, GitHub, Arcjet, JSON API                    |
| Deployment | Vercel                                               |

---

## 📸 Screenshots

| Dashboard View | Receipt Upload | Monthly Insights |
|----------------|----------------|------------------|
| *(Insert screenshots here if needed)* |

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/AtharvaBagade23/AI-Insurance-Platform.git
cd AI-Insurance-Platform
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up `.env.local`

Create a `.env.local` file and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_secret
NEXT_PUBLIC_SUPABASE_URL=your_url
SUPABASE_SERVICE_ROLE_KEY=your_key
INNGEST_API_KEY=your_key
ARCJET_SECRET_KEY=your_key
```

> Replace with your actual credentials

### 4. Start the development server

```bash
npm run dev
```

---

## 📬 Contributions

Pull requests are welcome! For major changes, open an issue first to discuss what you would like to change or improve.

---

## 🧑‍💻 Author

**Atharva Bagade**  
🔗 GitHub: [@AtharvaBagade23](https://github.com/AtharvaBagade23)

---

This project is for educational and demo purposes. Feel free to fork and customize it.
