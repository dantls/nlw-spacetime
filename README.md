# NLW Spacetime Server

This is the backend server for the NLW Spacetime project, designed as part of the Next Level Week (NLW) event. It handles the API logic, data storage, and communication with the frontend of the application.

## Table of Contents
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Technologies
- TypeScript
- Node.js
- Prisma (for database ORM)
- Express.js

## Setup
1. Clone the repository
   ```bash
   git clone https://github.com/dantls/nlw-spacetime-server.git
   ```
2. Navigate to the project folder:
   ```bash
   cd nlw-spacetime-server
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up the database by running the Prisma migrations:
   ```bash
   npx prisma migrate dev
   ```

## Usage
After setting up the server, you can start it using:
```bash
npm run dev
```
This will start the server locally, usually on `http://localhost:4000`.

## Project Structure
- `src/`: Contains the main server code.
- `prisma/`: Contains Prisma schema and migration files.

## License
This project is licensed under the MIT License.
