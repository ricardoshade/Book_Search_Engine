# Book Search Engine

## Description

The Book Search Engine is a full-stack MERN (MongoDB, Express.js, React, Node.js) application that allows users to search for books using the Google Books API and save their favorite books to a personal list. The application leverages GraphQL and Apollo Server for handling API requests and MongoDB for data storage.

## Features

- **Book Search**: Users can search for books by title, author, or keywords using the Google Books API.
- **User Authentication**: Secure user authentication with JWT (JSON Web Tokens).
- **Save Books**: Logged-in users can save books to their personal list.
- **View Saved Books**: Users can view their saved books and remove them if desired.
- **Responsive Design**: The application is designed to be responsive and user-friendly on various devices.

## Technologies Used

- **Frontend**:
  - React
  - Bootstrap
  - Apollo Client

- **Backend**:
  - Node.js
  - Express.js
  - Apollo Server
  - GraphQL
  - MongoDB
  - Mongoose
  - JWT (JSON Web Tokens)
  - bcryptjs

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ricardoshade/Book_Search_Engine.git
   cd Book_Search_Engine
   ```

2. **Install Dependencies**:
   ```bash
   npm run install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the `server` directory and add the following environment variables:
   ```
   MONGODB_URI=<your_mongodb_uri>
   JWT_SECRET=<your_jwt_secret>
   ```

4. **Build the Application**:
   ```bash
   npm run build
   ```

5. **Start the Application**:
   ```bash
   npm run develop
   ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Register a new account or log in with existing credentials.
3. Use the search bar to find books by title, author, or keywords.
4. Save books to your personal list by clicking the "Save this Book!" button.
5. View and manage your saved books in the "Saved Books" section.

## Project Structure

```
.
├── client
│   ├── public
│   └── src
│       ├── components
│       ├── pages
│       ├── utils
│       └── App.jsx
├── server
│   ├── config
│   ├── models
│   ├── schemas
│   ├── utils
│   └── server.js
├── .gitignore
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries, please contact Ricardo Shade at [ricardoshade@example.com](mailto:ricardoshade@example.com).

```
