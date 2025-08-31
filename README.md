# Excel Engineers - Boiler Parts Manufacturer

[![Next.js](https://img.shields.io/badge/Next.js-15.2.2-black)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-blue)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.17-38B2AC)](https://tailwindcss.com/)

A modern, responsive website for Excel Engineers - a leading manufacturer of high-quality boiler parts. Built with Next.js 15, React 19, TypeScript, and Tailwind CSS.

## 🚀 Features

- **Modern Web Technologies**: Built with Next.js 15 and React 19
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Type Safety**: Full TypeScript implementation
- **Component Library**: Rich UI components using Radix UI
- **Interactive Maps**: Integration with Leaflet and Mapbox GL
- **Form Handling**: Advanced forms with React Hook Form and Zod validation
- **Email Integration**: Nodemailer for contact forms
- **Database Ready**: MongoDB integration with Mongoose
- **Admin Panel**: Built-in administration interface
- **Blog System**: Content management for articles and news
- **Career Portal**: Job listings and application system
- **Project Showcase**: Portfolio of completed projects

## 🛠️ Tech Stack

### Frontend

- **Next.js 15** - React framework with App Router
- **React 19** - Latest React with concurrent features
- **TypeScript 5** - Type-safe JavaScript
- **Tailwind CSS 3.4** - Utility-first CSS framework
- **Radix UI** - Accessible component primitives
- **Lucide React** - Beautiful icon library

### Backend & Database

- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **Nodemailer** - Email functionality
- **Next.js API Routes** - Serverless API endpoints

### Additional Libraries

- **React Hook Form** - Performant forms with validation
- **Zod** - TypeScript-first schema validation
- **Leaflet & Mapbox GL** - Interactive maps
- **Recharts** - Data visualization
- **Date-fns** - Date utility library
- **Embla Carousel** - Touch-friendly carousel
- **Sonner** - Toast notifications

## 📁 Project Structure

```
excel-0.1-master/
├── app/                    # Next.js App Router
│   ├── about/             # About page
│   ├── admin/             # Admin panel
│   ├── api/               # API routes
│   ├── blog/              # Blog system
│   ├── careers/           # Career portal
│   ├── components/        # Shared components
│   ├── contact/           # Contact page
│   ├── projects/          # Project showcase
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Homepage
├── components/             # Reusable UI components
├── hooks/                  # Custom React hooks
├── lib/                    # Utility functions
├── models/                 # Database models
├── public/                 # Static assets
├── styles/                 # Additional styles
├── .next/                  # Build output
├── node_modules/           # Dependencies
├── package.json            # Project configuration
├── tsconfig.json          # TypeScript configuration
├── tailwind.config.js     # Tailwind CSS configuration
└── next.config.mjs        # Next.js configuration
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** 18.17 or later
- **npm** or **pnpm** package manager
- **Git** for version control

### Installation

1. **Clone the repository**

   ```bash
   git clone <your-repository-url>
   cd excel-0.1-master
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   pnpm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   NODEMAILER_EMAIL=your_email@example.com
   NODEMAILER_PASSWORD=your_email_password
   MAPBOX_ACCESS_TOKEN=your_mapbox_token
   ```

4. **Run the development server**

   ```bash
   npm run dev
   # or
   pnpm dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📱 Available Scripts

- **`npm run dev`** - Start development server
- **`npm run build`** - Build for production
- **`npm run start`** - Start production server
- **`npm run lint`** - Run ESLint

## 🌐 Pages & Features

### Main Pages

- **Homepage** - Company overview and hero section
- **About** - Company history and mission
- **Projects** - Portfolio of completed work
- **Blog** - Industry news and updates
- **Careers** - Job opportunities
- **Contact** - Get in touch with the team

### Admin Features

- Content management system
- Blog post editor
- Project management
- Career posting management
- Contact form submissions

### Interactive Elements

- Interactive maps showing company locations
- Contact forms with validation
- Project galleries and showcases
- Responsive navigation
- Dark/light theme support

## 🎨 Styling & Design

- **Tailwind CSS** for utility-first styling
- **Custom CSS** for specific components
- **Responsive design** for all screen sizes
- **Accessibility** focused with Radix UI components
- **Modern animations** with Tailwind CSS Animate

## 🔧 Configuration

### TypeScript

- Strict type checking enabled
- Path aliases configured
- Next.js types included

### Tailwind CSS

- Custom color palette
- Component variants
- Animation utilities
- PostCSS processing

### Next.js

- App Router enabled
- Image optimization
- API routes configured
- Static generation support

## 📊 Database Schema

The project includes MongoDB models for:

- **Blog Posts** - Articles and news
- **Projects** - Portfolio items
- **Careers** - Job listings
- **Contact Submissions** - Form data
- **Admin Users** - Authentication

## 🚀 Deployment

### Build for Production

```bash
npm run build
npm run start
```

### Environment Variables for Production

Ensure all required environment variables are set in your production environment:

- MongoDB connection string
- Email service credentials
- Mapbox access token
- Any other API keys

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is private and proprietary to Excel Engineers.

## 📞 Support

For support and questions:

- **Company**: Excel Engineers
- **Email**: [Contact through website]
- **Website**: [Your website URL]

## 🔄 Version History

- **v0.1.0** - Initial release with core functionality
  - Company website with responsive design
  - Blog and project management systems
  - Admin panel for content management
  - Contact forms and career portal

---

**Built with ❤️ by Excel Engineers Team**
