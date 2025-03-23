Google Books Search Engine

Description

A MERN stack web app using TypeScript that allows users to search for books via the Google Books API, create an account, save books, and manage their collection.

Live Demo

Google Books Search Engine

Installation

Clone the repository:

git clone git@github.com:Alioune-Ndoye/Google-books.git

Navigate into the project directory:

cd Google-books

Install dependencies:

npm install
npm install --save-dev typescript @types/node @types/react @types/express

Start the app:

npm start

Features

Search & Save Books: Search books and save favorites.

User Authentication: Sign up, log in, and manage saved books.

Remove Books: Delete books from saved list.

Logout: Secure user session management.

Technologies Used

Frontend: React, TypeScript, Bootstrap

Backend: Node.js, Express.js

Database: MongoDB (Mongoose ORM)

Auth: JSON Web Token (JWT)

API: Google Books API

Deployment: Render

Usage

Ensure Node.js and MongoDB are installed.

Start MongoDB:

mongod

Configure environment variables in .env:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Start the backend:

npm run server

Start the frontend:

npm start

Contributing

Fork the repo & create a feature branch.

Commit & push changes.

Submit a Pull Request.

License

MIT License.

