# Acme Dashboard

## Description

Acme Dashboard is a responsive web application built with Next.js and TypeScript, providing comprehensive features for managing customers, invoices, and tracking revenue. It leverages Tailwind CSS for styling and Vercel Postgres for data storage. The application includes secure user authentication managed by NextAuth.

## Features

- **User Authentication**: Secure login system using NextAuth with credentials provider.
- **Dashboard Overview**: View key metrics such as total invoices, customers, and revenue.
- **Customer Management**: View and manage customer information.
- **Invoice Management**: Create, edit, and manage invoices with status tracking.
- **Revenue Visualization**: Interactive charts to monitor monthly revenue.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Skeleton Loading**: Enhanced user experience with loading placeholders.

## Technologies Used

- [Next.js](https://nextjs.org/) - React framework for server-rendered applications.
- [TypeScript](https://www.typescriptlang.org/) - Typed superset of JavaScript.
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework.
- [NextAuth](https://next-auth.js.org/) - Authentication for Next.js applications.
- [Vercel Postgres](https://vercel.com/products/postgres) - Managed PostgreSQL database.
- [Heroicons](https://heroicons.com/) - Beautiful SVG icons.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/acme-dashboard.git
   cd acme-dashboard
   ```

2. **Install Dependencies**

   ```bash
   pnpm install
   # or
   npm install
   # or
   yarn install
   ```

3. **Set Up Environment Variables**

   Create a `.env.local` file in the root directory and add the following:

   ```env
   DATABASE_URL=your_vercel_postgres_connection_string
   NEXTAUTH_SECRET=your_nextauth_secret
   ```

4. **Run Database Migrations and Seed Data**

   ```bash
   pnpm run seed
   # or
   npm run seed
   # or
   yarn seed
   ```

5. **Start the Development Server**

   ```bash
   pnpm dev
   # or
   npm run dev
   # or
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Usage

- **Login**

  Navigate to `/login` and use the following credentials:

  ```
  Email: user@nextmail.com
  Password: 123456
  ```

- **Dashboard**

  Access the dashboard at `/dashboard` to view an overview of invoices, customers, and revenue.

- **Manage Customers**

  Go to `/dashboard/customers` to view and manage customer data.

- **Manage Invoices**

  Visit `/dashboard/invoices` to view, create, and edit invoices.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License

This project is licensed under the [MIT License](LICENSE).
