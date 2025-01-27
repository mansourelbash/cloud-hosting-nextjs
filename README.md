# Cloud Hosting Next.js Project

## Overview

This project is built with **Next.js** and demonstrates the development of a content management system with API routes, route handlers, and middleware for secure authentication. Users can:

- Create an account and sign in.
- Add articles (admin-only feature).
- Comment on articles.
- Admins can delete any comment made by users.

## Features

- **Role-based Access Control**: Admins have privileges to manage content and comments.
- **API Routes**: Scalable API endpoints built with Next.js for handling authentication, articles, and comments.
- **Middleware**: Secure authentication middleware using JWT.
- **Database Integration**: Powered by PostgreSQL for reliable data storage.

## Prerequisites

1. Install **PostgreSQL** locally or use a remote PostgreSQL server.
2. Set up environment variables as outlined below.

## Environment Variables

Create a `.env` file in the root directory and add the following:

```env
DATABASE_URL=your-database-uri
JWT_SECRET=your-jwt-secret-key
NODE_ENV=development
```

- Replace `your-database-uri` with the URI of your PostgreSQL database.
- Replace `your-jwt-secret-key` with a strong secret key for signing JWTs.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mansourelbash/cloud-hosting-nextjs.git
   cd cloud-hosting-nextjs
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to access the application.

## Project Structure

- **Frontend**: Built with the Next.js App Router.
- **Backend**: APIs implemented using Next.js API routes and handlers.
- **Authentication**: Middleware secures API endpoints with JWT.
- **Database**: Integrated with PostgreSQL for persistent data storage.

## Development Notes

- Modify pages in the `app/` directory. Changes are reflected immediately.
- Fonts are optimized using [`next/font`](https://nextjs.org/docs/basic-features/font-optimization).

## Deployment

Deploy the project using **Vercel** for seamless integration with Next.js:

1. Connect the GitHub repository to Vercel.
2. Configure environment variables in Vercel settings.
3. Deploy the application with one click.

For detailed instructions, refer to the [Next.js deployment guide](https://nextjs.org/docs/deployment).

## Learn More

Enhance your understanding of Next.js through these resources:

- [Next.js Documentation](https://nextjs.org/docs) for official documentation.
- [Learn Next.js](https://nextjs.org/learn) for an interactive tutorial.

---

This project was created by **Mansour ElBashabsheh** for educational purposes.

