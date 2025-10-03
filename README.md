# Cashflow

A web application for managing cash flow, consisting of a React-TypeScript frontend and Python FastAPI backend.

## Project Structure

```
cashflow/
├── frontend/          # React-TypeScript frontend with Vite
└── README.md
```

## Frontend

The frontend is built with:
- **React 19** with TypeScript
- **Vite** using rolldown-vite (experimental, powered by Rolldown)
- **ESLint** for code linting
- Hot Module Replacement (HMR) for fast development

### Getting Started with Frontend

```bash
cd frontend
npm install      # Dependencies are already installed
npm run dev      # Start development server
npm run build    # Build for production
npm run lint     # Run ESLint
npm run preview  # Preview production build
```

The development server will start at `http://localhost:5173/`