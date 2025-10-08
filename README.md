# QuickChat

A realtime/chat application.

## Table of Technologies

| Layer / Concern       | Technologies / Tools                                                                 |
|------------------------|----------------------------------------------------------------------------------------|
| Frontend               | React, CSS / SCSS, HTML, Axios (or fetch), WebSockets / Socket.io                     |
| Backend                | Node.js, Express.js                                                                    |
| Real-time / Communication | Socket.io                                                    |
| Database / Storage     | MongoDB                       |
| Environment / Runtime  | Node.js                                                                      |
| Package Management     | npm                                                                            |
| Build / Bundling        | Create React App / Webpack /                                          |
| Linting / Formatting    | ESLint, Prettier                                                          |
| Deployment / Dev ops    | Vercel                                          |

## Project Structure (based on repo)
/
├── client/ ← frontend React app
├── server/ ← backend Express / Node.js api
└── .gitignore


## Prerequisites

- Node.js installed (version ≥ 14 recommended)
- npm (comes with Node.js)  
- (If using a database) the database service running (e.g. MongoDB instance)

## Setup & Running

### 1. Clone the repo

```bash
git clone https://github.com/Devashish2077/QuickChat.git
cd QuickChat

# In root (optional, if dependencies are in subfolders)
npm install

# For client
cd client
npm install

# For server
cd ../server
npm install

# Run backend (server)
cd server
npm run dev   # or npm run server (whichever is configured)

# Run frontend (client)
cd ../client
npm start

# Build frontend
cd client
npm run build

# Serve backend (which may serve the built frontend)
cd ../server
npm start
 
