
# Hotel Website Management System

A fully-featured hotel management system built using Next.js, React, Sanity.io, Tailwind CSS, and Stripe. This project allows users to manage hotel rooms, perform bookings, handle payments, and much more. Based on a comprehensive YouTube tutorial by Code with Lari.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Acknowledgments](#acknowledgments)

## Features
- Hotel Room Management (CRUD) with Sanity.IO
- Hotel Room Reviews and Ratings
- Room Search by Type/Name
- Room Booking & Checkout using Stripe
- Stripe Webhook Integration
- Authentication with Auth.js (GitHub, Google, Email)
- Light/Dark Mode Toggle
- Responsive design with Tailwind CSS
- API Creation for Room Booking
- Middleware for security and session management
- Toast Notifications for user actions
- User Profile and Details Page
- Use of `useSwr` Hook for data fetching
- Typescript for static type-checking
- Deployment on Vercel

## Getting Started

To get started, clone the repository and install the dependencies:

```bash
git clone https://github.com/your-username/hotel-management-system.git
cd hotel-management-system
npm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.


## Technologies Used
- **Next.js** – React framework for server-side rendering and building full-stack web applications.
- **Sanity.io** – CMS for managing content, like hotel rooms and reviews.
- **Tailwind CSS** – Utility-first CSS framework for styling.
- **Stripe** – Payment gateway integration for booking and checkout.
- **Auth.js** – Handles authentication with providers like GitHub, Google, and email.
- **Typescript** – For static type checking and safer development.

## Deployment

This project is deployed on [Vercel](https://vercel.com/), which supports automatic deployments with GitHub integration. 

You can deploy your own version by following these steps:

1. Fork the repository.
2. Push the forked version to your GitHub account.
3. Link your repository to Vercel and deploy.

## Acknowledgments
This project is based on the excellent YouTube tutorial by [Code with Lari](https://www.youtube.com/@codewithlari). Special thanks for the in-depth guide on building and deploying the hotel management system!
