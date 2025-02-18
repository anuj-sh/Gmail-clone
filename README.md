# Gmail Clone

## Description

This project is a Gmail clone built using the MERN stack (MongoDB, Express, React, Node.js). It replicates the core functionalities of Gmail, including sending, receiving, and managing emails.

## Features

- User authentication and authorization
- Compose and send emails
- Receive and read emails
- Email management (inbox, sent, trash)

## Installation

Follow these steps to set up the project locally.

### Prerequisites

Make sure you have the following installed:

- Node.js
- MongoDB
- Git

### Setup

1. Clone the repository:
    sh
    git clone https://github.com/anuj-sh/gmail-clone.git
    cd gmail-clone
    

2. Install server dependencies:
    sh
    cd server
    npm install
    

3. Install client dependencies:
    sh
    cd ../client
    npm install
    

4. Create a .env file in the server directory and add the following:
    
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    

## Running the Application

1. Start the MongoDB server:
    sh
    mongod
    

2. Start the backend server:
    sh
    cd server
    npm start
    

3. Start the frontend development server:
    sh
    cd ../client
    npm start
    

4. Open your browser and navigate to http://localhost:3000.

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/YourFeature).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/YourFeature).
5. Open a Pull Request.

-
