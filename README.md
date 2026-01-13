# 🚀 FinTechCore

![FinTechCore Banner](public/logo.png)

> **your intelligent financial companion.**  
> Track, Analyze, and Master your finances with the power of AI.

---

## 🌐 Live Demo & Deployment

🚀 **Live Demo:** [Check out FinTechCore Live](https://fin-tech-core-fuxr79u11-khuhsiims-projects.vercel.app)

---

## ✨ Features

*   **🤖 AI-Powered Insights:** Personalized financial advice and budget tracking using Gemini AI.
*   **📊 Interactive Dashboard:** Real-time visualization of your income, expenses, and savings.
*   **💳 Smart Transaction Management:** Categorize and track every penny with ease.
*   **🔔 Intelligent Alerts:** Get notified about unusual spending or upcoming bills (via Inngest).
*   **🔒 Bank-Grade Security:** Secure authentication with Clerk and robust data protection with ArcJet.
*   **🎨 Modern UI/UX:** A sleek, responsive design built with Tailwind CSS and Shadcn UI.

---

## 🛠️ Tech Stack

*   **Framework:** [Next.js 15](https://nextjs.org/) (App Router)
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/) & [Shadcn UI](https://ui.shadcn.com/)
*   **Database:** [PostgreSQL](https://www.postgresql.org/) (via [Prisma ORM](https://www.prisma.io/))
*   **Auth:** [Clerk](https://clerk.com/)
*   **AI:** [Google Gemini](https://deepmind.google/technologies/gemini/)
*   **Backend Ops:** [Inngest](https://www.inngest.com/) & [ArcJet](https://arcjet.com/)

---

## ⚡ Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Khushiim1238/FinTechCore.git
cd FinTechCore
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Configure Environment
Create a `.env` file in the root directory and add your keys:

```ini
# Database (Prisma)
DATABASE_URL="postgresql://..."
DIRECT_URL="postgresql://..."

# Auth (Clerk)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_...
CLERK_SECRET_KEY=sk_test_...

# AI (Gemini)
GEMINI_API_KEY=...

# Other Services
RESEND_API_KEY=...
ARCJET_KEY=...
```

### 4️⃣ Run the App
```bash
npm run dev
```

Visit `http://localhost:3000` to see your app in action! 🚀

---

## 🤝 Contributing

Contributions are welcome! Feel free to maintain a fork and submit a Pull Request.

---

<p align="center">
  Built with ❤️ by <b>Khushiim1238</b>
</p>
