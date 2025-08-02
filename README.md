# Full Stack AI Fianace Platform 
An AI-powered personal finance tracker built using cutting-edge web technologies. The platform allows users to effortlessly manage expenses, visualize budgets, and extract data from receipts using AI. Designed with modern UI principles and built for scalability and real-time performance.
## 🛠️ Tech Stack

| Layer        | Technology                                      |
|--------------|--------------------------------------------------|
| Frontend     | React 19, Next.js 15, Tailwind CSS              |
| Backend      | Supabase (PostgreSQL), Prisma ORM               |
| Auth         | Clerk                                           |
| AI           | Gemini API (for receipt parsing & categorization) |
| Jobs         | Inngest                                         |
| ORM          | Prisma                                          |

### .env -

```
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
