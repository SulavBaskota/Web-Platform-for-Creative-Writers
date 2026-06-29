# Web Platform for Creative Writers

A modern web platform designed to help creative writers organize, develop, and share their writing projects. Built with cutting-edge web technologies for an intuitive and feature-rich user experience.

**[Project Report](https://github.com/SulavBaskota/mini-project/raw/main/Project%20Report.pdf)**

## Features

- 📝 **Project Management** - Create and organize multiple writing projects
- 👥 **User Authentication** - Secure authentication and authorization with NextAuth
- ✉️ **Email Notifications** - Send updates and notifications via Nodemailer
- 🖼️ **Image Management** - Upload and manage images via Cloudinary integration
- 🎨 **Material UI** - Beautiful and responsive user interface
- 💾 **Data Persistence** - MongoDB backend for reliable data storage
- 🔐 **Password Security** - Bcrypt encryption for secure password storage

## Tech Stack

### Frontend
- **Next.js** - React framework for production applications
- **React** - UI library for building interactive components
- **Material-UI (@mui/material)** - Comprehensive component library
- **Emotion** - CSS-in-JS styling solution

### Backend
- **Next.js API Routes** - Serverless backend functions
- **MongoDB** - NoSQL database for flexible data modeling
- **Mongoose** - MongoDB object modeling

### Authentication & Security
- **NextAuth.js** - Authentication library for Next.js
- **Bcrypt** - Password hashing and encryption

### Additional Services
- **Cloudinary** - Cloud image management and CDN
- **Nodemailer** - Email sending functionality

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/SulavBaskota/Web-Platform-for-Creative-Writers.git
cd Web-Platform-for-Creative-Writers
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Set up environment variables**
Create a `.env.local` file in the root directory with the following variables:
```
# MongoDB
MONGODB_URI=your_mongodb_connection_string

# NextAuth.js
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=http://localhost:3000 (Not required for Vercel deployment)

# Cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
NEXT_PUBLIC_CLOUDINARY_BOOK_PRESET=your_cloudinary_book_preset
NEXT_PUBLIC_CLOUDINARY_PROFILE_PRESET=your_cloudinary_profile_preset

# Nodemailer
NODEMAILER_HOST=your_email_host
NODEMAILER_USER=your_email
NODEMAILER_EMAIL=your_email@gmail.com
NODEMAILER_PASSWORD=your_app_password

# Vercel
NEXT_PUBLIC_VERCEL_URL=http://localhost:3000 (Not required for Vercel deployment)
```

4. **Run the development server**
```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm start` - Start the production server
- `npm run lint` - Run ESLint to check code quality

## Project Structure

```
├── pages/              # Next.js pages and API routes
├── components/         # Reusable React components
├── public/            # Static files
├── styles/            # Global styles and Emotion styled components
├── lib/               # Utility functions and helpers
└── package.json       # Project dependencies
```

## Key Technologies

| Technology | Purpose |
|-----------|---------|
| Next.js | React framework with server-side rendering and static generation |
| React | UI component library |
| Material-UI | React component library with pre-built UI components |
| MongoDB | NoSQL database for storing writer projects and user data |
| NextAuth.js | Authentication and session management |
| Cloudinary | Cloud-based image storage and manipulation |
| Nodemailer | Email sending for notifications |