# GBP Tracker

Track and manage your Google Business Profile locations.

## Project Structure

```
/
├── client/           # Frontend React application
└── server/           # Backend Node.js application
```

## Quick Start

### Frontend (Netlify)

```bash
cd client
npm install
npm run dev     # Development
npm run build   # Production build
```

### Backend (Railway)

```bash
cd server
npm install
npm run dev     # Development
npm run build   # Production build
npm start       # Start production server
```

## Deployment

### Frontend (Netlify)

1. Push to GitHub
2. Connect repository to Netlify
3. Configure build settings:
   - Build command: `cd client && npm install && npm run build`
   - Publish directory: `client/dist`
4. Set environment variables in Netlify dashboard

### Backend (Railway)

1. Push to GitHub
2. Connect repository to Railway
3. Configure service:
   - Root directory: `server`
   - Start command: `npm start`
4. Set environment variables in Railway dashboard