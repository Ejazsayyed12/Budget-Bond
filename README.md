# Budget Bond

A local Next.js budget-tracking app for a parent and one dependent.

## Stack

- Next.js
- React
- TypeScript
- Tailwind CSS
- MongoDB
- Mongoose
- NextAuth credentials login
- Chart.js

## Local setup

1. Start MongoDB locally.
2. Copy `.env.example` to `.env.local`.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open `http://localhost:3000`.

## Flow

1. Create a parent account.
2. Copy the generated family code from the success message.
3. Create the dependent account with that family code.
4. Parent logs in to set a monthly limit and send money.
5. Dependent logs in to add expenses and track remaining budget.
