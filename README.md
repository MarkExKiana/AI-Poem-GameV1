# AI-Poem-GameV1
A simple poem game made using AI - contributions are appreciated!

A full-stack TypeScript web application that allows users to interact with poems through various games.

## Features

- Display a collection of classic poems
- Interactive poem games:
  - Fill in the blank: Test your knowledge by filling in missing words
  - Rearrange: Challenge yourself by putting poem lines in the correct order
- Modern, responsive UI
- Type-safe codebase

## Tech Stack

- Next.js
- TypeScript
- Prisma (SQLite)
- Tailwind CSS

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Set up the database:
```bash
npx prisma generate
npx prisma db push
npx prisma db seed
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Database Schema

The application uses Prisma with SQLite for data storage. The schema includes:

- Poem: Stores poem information (title, author, content)
- Game: Stores game types associated with each poem

## Project Structure

- `/components`: Reusable React components
- `/pages`: Next.js pages and API routes
- `/prisma`: Database schema and migrations
- `/public`: Static assets

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request 
