# TripSync2

TripSync2 is a monorepo containing both the frontend and backend applications.

## Project Structure

```
TripSync2/
├── frontend/     # React Native/Expo frontend application
├── backend/      # Backend API server
└── package.json  # Root package.json for monorepo management
```

## Getting Started

### Install Dependencies

Install all dependencies for both frontend and backend:

```bash
npm run install:all
```

Or install them separately:

```bash
# Frontend
cd frontend
npm install

# Backend
cd backend
npm install
```

### Running the Applications

#### Frontend (React Native/Expo)

From the root directory:
```bash
npm run frontend:start      # Start Expo dev server
npm run frontend:android    # Run on Android
npm run frontend:ios        # Run on iOS
npm run frontend:web        # Run on web
```

Or from the frontend directory:
```bash
cd frontend
npm start
```

#### Backend

From the root directory:
```bash
npm run backend:start      # Start production server
npm run backend:dev         # Start development server with nodemon
```

Or from the backend directory:
```bash
cd backend
npm start      # Production
npm run dev    # Development
```

## Frontend

The frontend is built with React Native and Expo. See `frontend/README.md` for more details.

## Backend

The backend API server. See `backend/README.md` for more details.
