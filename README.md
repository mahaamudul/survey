# Survey Platform — Create, Share & Earn

A full-stack survey platform where businesses create surveys and users earn rewards for completing them.

## Features

**For Survey Creators**
- **Create from Scratch** — Build custom surveys with a visual editor
- **Create with AI** — Generate surveys automatically using AI
- **Duplicate & Edit** — Copy existing surveys and customise them
- **Publish & Distribute** — Publish surveys and track responses
- **Analytics Dashboard** — Response rates, completion stats, and insights

**For Respondents**
- **Earn Rewards** — Complete surveys and earn tokens
- **Level System** — Progress through levels as you complete more surveys
- **Cash Out** — Redeem tokens for real rewards
- **Featured Tests** — High-reward featured surveys
- **Track History** — View all completed surveys and earnings

## Tech Stack

**Frontend** (`survey-client`)

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

- React + Vite SPA
- Tailwind CSS
- Firebase Authentication
- Context API for state management

**Backend** (`survey-server`)

- Node.js / Express REST API
- MongoDB database
- JWT + Firebase auth

## Project Structure

```
├── survey-client/           # React + Vite frontend
│   ├── src/
│   │   ├── Pages/           # Route-level pages (Dashboard, Home, Create...)
│   │   ├── components/      # UI components by section
│   │   ├── providers/       # Auth & navigation context
│   │   ├── hooks/           # Custom React hooks
│   │   └── firebase/        # Firebase config
│   └── public/
└── survey-server/           # Node.js backend
    ├── models/
    ├── routes/
    └── middleware/
```

## Getting Started

**Frontend**
```bash
cd survey-client
npm install
# Add Firebase config to src/firebase/firebase.config.js
npm run dev
```

**Backend**
```bash
cd survey-server
npm install
# Add your .env (MongoDB URI, JWT secret)
npm start
```
