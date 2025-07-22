
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
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
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
