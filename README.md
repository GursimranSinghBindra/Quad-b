Getting Started
These instructions will guide you in setting up the project on your local machine for development and testing purposes.

Prerequisites
NPM or Yarn
Node.js
.env Setup
In the server/.env file, replace the placeholders with your own API key, as the provided key may not work in the future.

env
Copy code
BRAINTREE_MERCHANT_ID=your_id
BRAINTREE_PUBLIC_KEY=your_public_key
BRAINTREE_PRIVATE_KEY=your_private_key
Installing Dependencies
Install NPM modules in both the client and server folders.

Run these commands from the project directory:

bash
Copy code
cd client && npm install
cd server && npm install
Running the App
To run the app locally, follow these steps:

Open a terminal in the server directory and run:
bash
Copy code
npm run start:dev
Open another terminal in the client directory and run:
bash
Copy code
npm run start
Access the web app at http://localhost:3000/.
