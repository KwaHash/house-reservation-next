# HouseCloud - House Reservation System

HouseCloud is a modern web application built with Next.js 14 that provides a comprehensive house reservation and management system. This platform allows users to browse, book, and manage property reservations with a beautiful and intuitive interface.

## Features

- 🏠 Property Listing and Management
- 🔐 User Authentication and Authorization
- 📅 Reservation System
- 🗺️ Google Maps Integration
- 📝 Rich Text Editor (CKEditor 5)
- 📱 Responsive Design
- 🌐 API Integration
- 📧 Email Notifications (SendGrid)
- 🔒 Secure Authentication (JWT)
- 🎨 Modern UI with Material-UI and TailwindCSS

## Tech Stack

- **Framework**: Next.js 14
- **Language**: TypeScript
- **Styling**: TailwindCSS, Material-UI, Emotion
- **State Management**: Recoil
- **Form Handling**: React Hook Form, Yup
- **Database**: MySQL
- **Authentication**: JWT, bcrypt
- **APIs**: SendGrid, Google Maps
- **Other Tools**: Node-cron, UUID, React Icons

## Getting Started

1. Clone the repository:
```bash
git clone [https://github.com/KwaHash/house-reservation-next.git]
cd next-house-reservation
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory with the following variables:
```env
# Database
DATABASE_URL=your_database_url

# Authentication
JWT_SECRET=your_jwt_secret

# APIs
SENDGRID_API_KEY=your_sendgrid_api_key
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
```

4. Run the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build production application
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Project Structure

- `/app` - Next.js app router pages and API routes
- `/components` - Reusable React components
- `/features` - Feature-specific components and logic
- `/context` - React context providers
- `/lib` - Utility libraries and configurations
- `/types` - TypeScript type definitions
- `/utils` - Helper functions and utilities
- `/public` - Static assets
