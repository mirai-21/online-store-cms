# E-commerce Platform on Next.js, Nest.js & Prisma

## Overview

This is a full-featured e-commerce store with a built-in CMS (Content Management System), created on a modern technology stack: **Next.js** (Frontend), **Nest.js** (Backend), and **Prisma** (ORM).

The project is a high-performance and scalable e-commerce solution that allows users to conveniently browse and purchase products. A key feature is the secure and fast authentication via **Google**. Administrators and store owners get a user-friendly panel to manage content: products, orders, and store settings.

### Features

- **User authentication and authorization:** Convenient and secure login for users via **Google**.
- **Admin Panel (CMS):** An intuitive panel for managing stores, products, and orders.
- **Store management:** Full CRUD (Create, Read, Update, Delete) functionality for stores.
- **Product management:** Easily add, edit, and delete products in your stores.
- **Order management:** Track and update order statuses.
- **Payment processing:** Payment processing using **Stripe**.
- **Real-time updates:** Instant notifications and status updates thanks to **WebSockets**.

## Technologies Used

- **Next.js** (Frontend Framework)
- **Nest.js** (Backend Framework)
- **Prisma** (ORM / Database)
- **Google OAuth** (Authentication)
- **Stripe** (Payment Gateway)
- **WebSockets** (Real-time updates)

## Project Structure

The project is divided into two main folders: `client-side` and `server-side`.

### Server-side

- `server-side`: This folder contains the Nest.js backend code, including API endpoints, database models (Prisma), services, and business logic.

### Client-side

- `client-side`: This folder contains the Next.js frontend code, including components, pages, navigation logic, and services for interacting with the API.

## Installation

To set up the project locally, follow these steps:

1.  **Clone the repository** using `git clone https://github.com/mirai-21/online-store-cms`.
2.  **Install the dependencies** for the server (`server-side`) and client (`client-side`) using `npm install` or `yarn install`.
3.  **Configure environment variables**: Create a `.env` file in the `server-side` folder by copying `env.example`. Update the `DATABASE_URL` and add your keys for Stripe, Google OAuth.
4.  **Start the server** using `npm run start:dev` in the `server-side` folder.
5.  **Start the client** using `npm run dev` in the `client-side` folder.
