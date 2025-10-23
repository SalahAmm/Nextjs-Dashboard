# Next.js Dashboard

A modern dashboard application built with Next.js, featuring customer and invoice management.

## Features

- **Dashboard Overview** - View key metrics and summaries
- **Customer Management** - Browse and manage customer data
- **Invoice Management** - Create, view, and manage invoices
- **Authentication** - Secure login with NextAuth
- **Database Integration** - PostgreSQL database with seeding capabilities

## Tech Stack

- **Framework**: Next.js 16 (Canary) with Turbopack
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Authentication**: NextAuth v5
- **Database**: PostgreSQL (via `postgres` package)
- **Icons**: Heroicons
- **Validation**: Zod

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- pnpm package manager
- PostgreSQL database

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Set up your environment variables (create a `.env` file)

4. Seed the database:
   ```bash
   # Visit /seed endpoint or run seed script
   ```

### Development

Run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build

Build for production:

```bash
pnpm build
```

### Start Production Server

```bash
pnpm start
```

## Project Structure

- `/app` - Next.js app directory with routes and components
  - `/dashboard` - Dashboard pages (overview, customers, invoices)
  - `/lib` - Utility functions, actions, and data definitions
  - `/ui` - Reusable UI components
- `/public` - Static assets

## License

Private project
