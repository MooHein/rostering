# Rostering

Employee rostering and shift management application.

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Set up environment variables:

   - Copy `.env.local.example` to `.env.local`
   - Add your Clerk keys from [clerk.com](https://clerk.com)
   - Set up your database URL in `.env`

3. Generate Prisma client:

   ```bash
   npm run db:generate
   ```

4. Push database schema:

   ```bash
   npm run db:push
   ```

5. Run the development server:
   ```bash
   npm run dev
   ```

Open [http://localhost:3000](http://localhost:3000) to view the app.

## Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS + shadcn/ui
- **Authentication**: Clerk
- **Database**: PostgreSQL + Prisma
- **Validation**: Zod
- **Icons**: Lucide React
