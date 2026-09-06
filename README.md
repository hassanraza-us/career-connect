# Career Connect

Career Connect is a full-stack job board that allows employers to submit job opportunities and helps candidates search for relevant positions.

## Features

* Search jobs by keyword
* Filter by job type, location, and remote availability
* View detailed job descriptions
* Submit new job postings
* Upload company logos
* Validate submitted information
* Review and approve postings through an admin dashboard
* Apply using an email address or external application link
* Responsive design for desktop and mobile devices

## Technologies

* Next.js
* React
* TypeScript
* Tailwind CSS
* PostgreSQL
* Prisma ORM
* Clerk Authentication
* Zod validation
* Vercel Blob

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/hassanraza-us/career-connect.git
cd career-connect
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file and add your database, Clerk, and Vercel Blob credentials.

Never commit `.env.local` or private credentials to GitHub.

### 4. Prepare the database

```bash
npx prisma generate
npx prisma db push
```

### 5. Start the application

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser.

## Future Improvements

* Candidate and employer accounts
* Saved jobs
* Application tracking
* Email notifications
* Automated testing
* Improved accessibility

## Author

Hassan Raza
MS Computer Science Student at the University at Albany, SUNY
[LinkedIn](https://www.linkedin.com/in/hassanrazaus/)
