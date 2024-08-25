# E-Commerce Website with Admin Dashboard

Welcome to the comprehensive guide for building and deploying a full-stack integrated E-Commerce website with an Admin Dashboard. This project utilizes cutting-edge technologies like Next.js 14, Stripe, TypeScript, MongoDB, Clerk, React-Hook-Form, Tailwind CSS, Shadcn UI, and Next Cloudinary. This README will provide you with everything you need to get started, from setting up the project to deploying it.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Environment Variables](#environment-variables)
  - [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Key Functionalities](#key-functionalities)
  - [Authentication & User Management](#authentication--user-management)
  - [Product & Collection Management](#product--collection-management)
  - [Search, Wishlist, and Cart](#search-wishlist-and-cart)
  - [Order Management](#order-management)
  - [Admin Dashboard](#admin-dashboard)
  - [Responsive UI Design](#responsive-ui-design)
  - [Image Upload & Storage](#image-upload--storage)
- [Deployment](#deployment)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project aims to build a scalable and responsive e-commerce platform with a fully functional admin dashboard. The application is built with Next.js 14 and leverages the latest features, including server-side and client-side rendering, layout route groups, and more. The project also integrates with third-party services like Stripe for payment processing, Clerk for authentication, and Cloudinary for image storage, providing a seamless user experience.

## Features

- **Next.js 14**: Master server-side and client-side rendering using the latest features of Next.js 14, including the App Router.
- **Clerk Integration**: Implement robust authentication and user management with Clerk.
- **Product Management**: Create, update, and manage product collections with form validation using React-Hook-Form.
- **Admin Dashboard**: A comprehensive dashboard to manage products, orders, and customers, complete with data tables and search functionality.
- **Stripe Integration**: Seamlessly handle checkout and order creation with Stripe.
- **MongoDB**: Manage data with MongoDB, including handling nested schemas and relationships.
- **Responsive Design**: Build a stunning and responsive UI using Tailwind CSS, Shadcn UI, and Recharts for data visualization.
- **Cloudinary**: Efficient image upload and storage using Next Cloudinary.

## Tech Stack

- **Frontend**: Next.js 14, TypeScript, React-Hook-Form, Tailwind CSS, Shadcn UI
- **Backend**: Next.js API Routes, MongoDB
- **Authentication**: Clerk
- **Payments**: Stripe
- **Image Storage**: Cloudinary
- **State Management**: React Context API
- **Forms**: React-Hook-Form

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- Node.js (v14 or later)
- npm or yarn
- MongoDB (local or Atlas)
- Stripe account
- Clerk account
- Cloudinary account

## Getting Started

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/ecommerce-nextjs.git
   cd ecommerce-nextjs
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Application

To start the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application in action.

## Key Functionalities

### Authentication & User Management

- Implemented using **Clerk**.
- Users can sign up, log in, and manage their profiles.
- Admin users have additional privileges to access the dashboard.

### Product & Collection Management

- Create and manage products and collections.
- Form validation handled by **React-Hook-Form**.
- Products are stored in **MongoDB** with nested schemas for efficient querying.

### Search, Wishlist, and Cart

- Integrated search functionality with a dynamic search bar.
- Users can add products to their wishlist and shopping cart.
- Real-time updates and feedback using **React Context API**.

### Order Management

- Checkout process integrated with **Stripe** for secure payment processing.
- Orders are stored in MongoDB and accessible via the admin dashboard.

### Admin Dashboard

- A robust admin dashboard built with **Next.js App Router**.
- Manage products, orders, and customers.
- Data tables with search functionality.

### Responsive UI Design

- Built with **Tailwind CSS** and **Shadcn UI**.
- Responsive design ensures a seamless experience across devices.
- **Recharts** used for visualizing sales data in the admin dashboard.

### Image Upload & Storage

- Integrated with **Cloudinary** for image upload and storage.
- Users can upload product images, which are optimized and stored in Cloudinary.

## Deployment

To deploy the application, follow these steps:

1. **Build the project:**

   ```bash
   npm run build
   # or
   yarn build
   ```

2. **Deploy to Vercel:**
   - Connect your GitHub repository to Vercel.
   - Vercel will automatically build and deploy your project.

## Learning Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Clerk Documentation](https://docs.clerk.dev/)
- [Stripe Documentation](https://stripe.com/docs)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [React-Hook-Form Documentation](https://react-hook-form.com/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Cloudinary Documentation](https://cloudinary.com/documentation)

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

Happy coding! 🚀
