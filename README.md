# ChatApp

Welcome to ChatApp! This guide will help you set up and run the application on your local machine.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Git](https://git-scm.com/)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Icebear137/chatapp.git
   cd chatapp
   ```

2. Set up the backend:

   ```bash
   cd backend
   cp .env.example .env
   npm install
   node src/seeds/user.seed.js
   ```

3. Set up the frontend:
   ```bash
   cd ../frontend
   npm install
   ```

## Running the Application

1. Start the backend server:

   ```bash
   cd backend
   npm run dev
   ```

2. In a new terminal, start the frontend:

   ```bash
   cd frontend
   npm run dev
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:5173
   ```

## Features

- Real-time messaging
- User authentication
- Responsive design

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or support, please contact [your-email@example.com](mailto:your-email@example.com).
