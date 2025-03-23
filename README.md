# Google Books Search Engine

## Description
A MERN stack web app using TypeScript that allows users to search for books via the Google Books API, create an account, save books, and manage their collection.

## Live Demo
[Google Books Search Engine](https://google-books-o5hg.onrender.com)

## Installation
1. Clone the repository:
   ```sh
   git clone git@github.com:Alioune-Ndoye/Google-books.git
   ```
2. Navigate into the project directory:
   ```sh
   cd Google-books
   ```
3. Install dependencies:
   ```sh
   npm install
   npm install --save-dev typescript @types/node @types/react @types/express
   ```
4. Start the app:
   ```sh
   npm start
   ```

## Features
- **Search & Save Books**: Search books and save favorites.
- **User Authentication**: Sign up, log in, and manage saved books.
- **Remove Books**: Delete books from saved list.
- **Logout**: Secure user session management.

## Technologies Used
- **Frontend**: React, TypeScript, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ORM)
- **Auth**: JSON Web Token (JWT)
- **API**: Google Books API
- **Deployment**: Render

## Usage
1. Ensure **Node.js** and **MongoDB** are installed.
2. Start MongoDB:
   ```sh
   mongod
   ```
3. Configure environment variables in `.env`:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```
4. Start the backend:
   ```sh
   npm run server
   ```
5. Start the frontend:
   ```sh
   npm start
   ```

## Contributing
1. Fork the repo & create a feature branch.
2. Commit & push changes.
3. Submit a Pull Request.

## License
MIT License.

## Contact
For questions or contributions, visit [GitHub](https://github.com/Alioune-Ndoye).

