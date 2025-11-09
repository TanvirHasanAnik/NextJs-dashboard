# Project Overview

This is a Next.js project bootstrapped with `create-next-app`. It seems to be a dashboard application for managing customers and invoices. The project uses Tailwind CSS for styling and Postgres for the database.

## Building and Running

To get the development server running, use the following command:

```bash
pnpm dev
```

To create a production build, use:

```bash
pnpm build
```

And to start the production server, use:

```bash
pnpm start
```

## Development Conventions

The project uses TypeScript and follows the standard Next.js project structure. It uses the App Router. Data fetching is done in the `app/lib/data.ts` file, which uses the `postgres` library to query the database. The UI components are located in the `app/ui` directory.
