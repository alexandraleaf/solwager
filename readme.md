# SolWager Platform

An easily customizable Solana template featuring multiple on-chain games.

Simply fork the repository, provide your own Solana address, and begin collecting fees on every bet made via your frontend. No liquidity is needed from your end as it is already provided on SolWager.

## 🚀 Features

- Multiple customizable on-chain games (BlackJack, Dice, Roulette, Slots, etc.)
- Custom SPL tokens
- Provably fair results
- Bonuses system
- Real-time betting with Solana blockchain
- Responsive web interface

## 💻 Tech Stack

### Frontend
- **Framework:** React with TypeScript
- **Build Tool:** Vite
- **Styling:** CSS Modules
- **State Management:** Custom hooks and Zustand
- **Web3 Integration:** Solana Web3.js

### Backend
- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT tokens
- **File Upload:** Multer
- **Email:** Nodemailer

## 📦 Getting Started

### Prerequisites
- Node.js v20
- MongoDB database
- Solana wallet

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/alexandraleaf/solwager
   cd main
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development servers:**
   ```bash
   npm start
   ```

4. Open [http://localhost:5173](http://localhost:5173) to view the app.

## 🗂 Project Structure

```
solwager/
├── public/                 # Static assets
│   ├── manifest.webmanifest
│   └── games/             # Game assets
├── src/                   # Frontend React app
│   ├── components/        # Reusable UI components
│   ├── games/            # Game components
│   │   ├── BlackJack/
│   │   ├── Dice/
│   │   ├── Roulette/
│   │   └── ...
│   ├── hooks/            # Custom React hooks
│   ├── sections/         # Page sections
│   └── utils.ts          # Utility functions
├── server/               # Backend Node.js server
│   ├── controllers/      # Route controllers
│   ├── middlewares/      # Express middlewares
│   ├── models/          # MongoDB models
│   ├── routes/          # API routes
│   └── utils/           # Server utilities
├── api/                 # API endpoints (if any)
└── index.html           # Main HTML file
```

## 🎮 Available Games

- **BlackJack** - Classic card game
- **Dice** - Simple dice betting
- **Roulette** - Wheel of fortune
- **Slots** - Slot machine
- **Plinko** - Ball drop game
- **Mines** - Mine sweeper betting
- **Crash** - Multiplier crash game
- **HiLo** - Higher/Lower prediction
- **Jackpot** - Progressive jackpot
- **Flip** - Coin flip betting
- **PvpFlip** - Player vs Player coin flip

## 📄 License

This project is licensed under the MIT License.
