# Trinity Monuments - StackBlitz Setup

## 🚀 Quick Setup Instructions

### 1. Create New React Project in StackBlitz
- Go to [stackblitz.com](https://stackblitz.com)
- Click "Create project"
- Choose "Vite + React + TypeScript"

### 2. Replace Default Files
Copy all the files from this project into your StackBlitz project:

#### Core Files:
- `package.json` - Dependencies and scripts
- `vite.config.ts` - Build configuration
- `tailwind.config.js` - Styling configuration
- `tsconfig.json` - TypeScript configuration
- `index.html` - Main HTML template

#### Source Files:
- Copy entire `src/` folder
- Copy entire `public/` folder

### 3. Install Dependencies
StackBlitz will automatically install dependencies from package.json:
```json
{
  "dependencies": {
    "@supabase/supabase-js": "^2.53.0",
    "date-fns": "^4.1.0",
    "lucide-react": "^0.263.1",
    "react": "^18.3.1",
    "react-dom": "^18.3.1",
    "react-router-dom": "^6.30.1",
    "react-to-print": "^2.15.1"
  }
}
```

### 4. Environment Variables
Create `.env` file in StackBlitz:
```
VITE_SUPABASE_URL=https://fygancbjlfmlwrsvvsfs.supabase.co
VITE_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6ImZ5Z2FuY2JqbGZtbHdyc3Z2c2ZzIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NTQ0MTEyMTUsImV4cCI6MjA2OTk4NzIxNX0.bSPbN7xNGaglNHYNqq0pvgICqkppMMb2ydQuVGaJR9c
```

### 5. Key Features
- ✅ Complete monument business website
- ✅ Admin dashboard with order management
- ✅ Digital memorial pages with QR codes
- ✅ Granite color catalog
- ✅ Contact forms and quote requests
- ✅ Mobile-optimized performance
- ✅ Supabase database integration

### 6. Admin Access
- **URL**: `/admin` or `/admin-dashboard`
- **Password**: `Trinity2024`

### 7. Live Demo
Current live site: https://magnificent-gelato-de73fc.netlify.app

## 📋 File Structure
```
trinity-monuments/
├── public/
│   ├── manifest.json
│   ├── robots.txt
│   └── sitemap.xml
├── src/
│   ├── components/
│   ├── pages/
│   ├── lib/
│   └── main.tsx
├── package.json
├── vite.config.ts
└── tailwind.config.js
```

## 🎯 Next Steps
1. Copy all files to StackBlitz
2. Wait for dependencies to install
3. Run the development server
4. Access admin at `/admin` with password `Trinity2024`