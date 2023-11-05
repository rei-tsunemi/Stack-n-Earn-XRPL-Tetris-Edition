# Stack-N-Earn XRPL

Stack-N-Earn XRPL is a Tetris-like game that integrates with the XRP Ledger, allowing players to earn XRP as they score points in the game. It's built with React for the frontend and a Node.js server to handle XRP transfers on the XRPL Testnet.

## Overview

The game rewards players with XRP based on their score. Players enter their XRPL Testnet wallet address, play the game, and can claim their earned XRP, which is then transferred to the provided wallet address.

## Installation

To set up the Stack-N-Earn XRPL project, follow these steps:

### Prerequisites

- Node.js and npm (Node Package Manager)
- An XRPL Testnet wallet address

### Setup

1. Clone the repository:
   ```git clone https://github.com/yourusername/stack-n-earn-xrpl.git```

2. Navigate to the project directory:
``` cd stack-n-earn-xrpl```
3. Install dependencies for the server and frontend:
```npm install```

### Usage

To run the game locally, follow these steps:

1. Start the backend server:

```cd server```
```node server.js```

2. In a new terminal, navigate to the frontend directory and start the React app:
```npm start watch```

3. Run the html document in ./dist with live server
4. Enter your XRPL Testnet wallet address, play the game, and click "Claim XRP" to transfer your earned XRP to your wallet.

