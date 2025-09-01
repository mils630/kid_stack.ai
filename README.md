# Kid.Stack AI Academy

A modern, AI-powered coding education platform for kids aged 7-17.

## Project Structure

```
kid_stack.ai/
├── kidstack-ai-academy/     # Main React/Vite application
│   ├── src/                 # Source code
│   ├── public/              # Static assets
│   ├── package.json         # Dependencies
│   └── vite.config.ts       # Vite configuration
├── vercel.json              # Vercel deployment configuration
└── README.md               # This file
```

## Deployment

This project is configured for Vercel deployment with:
- **Root Directory**: `kidstack-ai-academy`
- **Build Command**: `npm run build`
- **Output Directory**: `dist`
- **Framework**: Vite

## Environment Variables

Required for Supabase integration:
- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_ANON_KEY`

## Development

```bash
cd kidstack-ai-academy
npm install
npm run dev
```

## Tech Stack

- **Frontend**: React 18 + TypeScript + Vite
- **Styling**: Tailwind CSS + shadcn/ui
- **Backend**: Supabase (Database, Auth, Storage)
- **Deployment**: Vercel
- **Routing**: React Router DOM
- **State Management**: TanStack Query
- **Forms**: React Hook Form + Zod
