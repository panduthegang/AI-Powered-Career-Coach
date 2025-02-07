# SenSAI: Your AI Career Companion 🚀🤖

## Preview

![SenSAI Application Preview](/public/preview.png)

## Vision
Transform career development through intelligent, personalized AI guidance.

## 🌟 Key Features

🔍 **Smart Career Insights**
- Real-time industry trend analysis
- Personalized career path recommendations
- Global job market intelligence

💼 **Professional Branding**
- AI-powered resume optimization
- Intelligent cover letter generation
- Personal brand strategy builder

🧠 **Skill Development**
- Adaptive skill gap identification
- Customized learning roadmaps
- Interactive AI-driven skill quizzes

🤝 **Interview Mastery**
- AI interview question generator
- Behavioral analysis toolkit
- Confidence-building practice sessions

🌐 **Networking & Opportunities**
- LinkedIn profile enhancement
- Career community connections
- Targeted job recommendation engine

## 🛠 Tech Ecosystem
- Next.js 14
- Neon PostgreSQL
- Prisma ORM
- Tailwind CSS
- Shadcn UI
- Clerk Authentication
- Gemini AI
- Inngest

## 🚀 Quick Start

```bash
# Clone Repository
git clone https://github.com/panduthegang/AI-Powered-Career-Coach.git

# Install Dependencies
npm install

# Prisma Migrate
npx prisma generate
npx prisma migrate dev

# Start the Application
npm run dev
```

## 🔐 Environment Setup
### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```
Rename `.env.example` to `.env` and configure:
- Database credentials
- Clerk authentication keys
- Gemini AI integration
