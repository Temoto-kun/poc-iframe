This is a simple proof-of-concept for cross-window communication through iframes.

# Requirements

- Node.js (enough to run Express.js)
- Yarn

# How to install

1. Clone this repo
2. Navigate to `/child`
3. Install dependencies: `yarn install`
4. Run the child: `PORT=<port> yarn start` (`PORT` defaults to `3001` when unspecified)
5. Navigate to `/parent`
6. Install dependencies: `yarn install`
7. Run the parent: `PORT=<port> yarn start` (`PORT` defaults to `3000` when unspecified)
8. View the parent in the browser through: `http://localhost:<PORT>` (`PORT` is the parent port specified on step 7).
