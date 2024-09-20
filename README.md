# Next.js with Prisma Setup

This repository provides a standard setup for building Next.js applications integrated with Prisma as the ORM. Follow the instructions below to clone and use this project for your development.

## Features

- **Standardized Project Structure:** Organized folder layout for clarity.
- **Prisma Integration:** Pre-configured Prisma schema and client setup.
- **Database Seeding:** Seed script to populate your database with initial data.
- **TypeScript Support:** Fully configured TypeScript for type safety.
- **Easy Setup:** Step-by-step instructions for getting started.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/download/) (>= 14.x)
- npm or Yarn
- A PostgreSQL database (or other supported databases)


## Installation

Clone the repository:

Install the dependencies and devDependencies and start the server.

```sh
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

Install dependencies:
```sh
npm install
# or
yarn install
```
Set up environment variables: Create a `.env` file in the root of the project and configure your database connection:

```plaintext
DATABASE_URL="postgresql://USER:PASSWORD@localhost:5432/DATABASE_NAME"
```

Run Prisma migrations: Initialize your database and apply migrations:


```sh
npx prisma migrate dev --name init
```

Seed the database (optional): If you want to populate your database with initial data:
```sh
npm run dev
# or
yarn dev
```
**Run the application:** Start the development server:

1. **Open your browser:** 
   Visit [http://localhost:3000](http://localhost:3000) to see your application running.


## Usage


You can start building your Next.js application by adding components, pages, and API routes as needed. Use the Prisma client to interact with your database in your application logic.

## Contributing

If you would like to contribute to this project, feel free to submit a pull request or open an issue.
## License
This project is licensed under the MIT
