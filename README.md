# Trinity Monuments Website

A complete monument and memorial services website built with React, TypeScript, and Tailwind CSS.

## 🚀 Live Site

Visit the live website at: [trinity-monuments.com](https://trinity-monuments.com)

## 📋 Deployment

This site is automatically deployed to Netlify when changes are pushed to the main branch on GitHub.

## Features

- **Public Website**: Products, services, granite colors, contact forms
- **Digital Memorials**: QR code accessible memorial pages
- **Admin System**: Order management and customer tracking
- **Database Integration**: Supabase backend for order storage

## 🔧 Development Workflow

1. Make changes in StackBlitz
2. Commit and push to GitHub
3. Netlify automatically builds and deploys
4. Changes go live at trinity-monuments.com

## Setup Instructions

### 1. Install Dependencies
```bash
npm install
```

### 2. Environment Setup
Create a `.env` file in the root directory with your Supabase credentials:
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 3. Database Setup
The project uses Supabase with the following table structure:
- `orders` table with customer information, monument details, pricing, and tracking dates

### 4. Development
```bash
npm run dev
```

### 5. Build for Production
```bash
npm run build
```

The built files will be in the `dist/` folder, ready for upload to your hosting provider.

## Admin Access

- **Admin Form**: `/admin` (Password: Trinity2024)
- **Admin Dashboard**: `/admin-dashboard` (Password: Trinity2024)

## File Structure

- `src/components/` - Reusable React components
- `src/pages/` - Page components
- `src/lib/` - Supabase configuration
- `public/` - Static assets
- `dist/` - Built files for production

## Important Files

- `package.json` - Dependencies and scripts
- `vite.config.ts` - Build configuration
- `tailwind.config.js` - Styling configuration
- `index.html` - Main HTML template
- `.env` - Environment variables (create this)

## Deployment

1. Run `npm run build`
2. Upload the contents of the `dist/` folder to your web hosting
3. Ensure your hosting supports single-page applications (SPA)
4. Configure redirects to serve `index.html` for all routes

## Support

For questions about this codebase, refer to the component files and configuration.