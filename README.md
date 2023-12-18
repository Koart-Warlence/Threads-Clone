# Threads Clone

**Threads Clone** is a project inspired by Threads, serves as a prototype imitation designed to familiarize users with Next.js 13, TypeScript, shadcn/ui, MongoDB, and third-party authentication via Clerk. The application is also deployed on Vercel for seamless accessibility and use.

## Installation

1. Install dependencies:

   ```
   npm install
   ```

2. Set up environment variables: Create a `.env.local` file in the project root and configure the following environment variables:

   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=YOUR_PUBLIC_CLERK_PUBLISHABLE_KEY
   CLERK_SECRET_KEY=YOUR_CLERK_SECRET_KEY

   NEXT_CLERK_WEBHOOK_SECRET=YOUR_WEBHOOK_SECRET

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

   MONGODB_URL=YOUR_MONGODB_CONNECTION_STRING

   UPLOADTHING_SECRET=YOUR_UPLOADTHING_SECRET
   UPLOADTHING_APP_ID=YOUR_UPLOADTHING_APP_ID
   ```

   Make sure to replace these values with the respective actual values.

3. Start the project:

   ```
   npm run dev
   ```

   The project will run at `http://localhost:3000`.

## Key Features

- **User Registration and Login:**
  - Secure user registration and login functionality using Clerk and third-party authentication services.
- **Communities and Threads:**
  - Users can create Communities and post threads within or without Communities.
- **Comments and Replies:**
  - Users can leave comments on threads and reply to comments.
- **Profile Editing:**
  - Users can edit their profiles, including avatars and personal bios.
- **Clean User Interface:**
  - Utilizes shadcn/ui for clean, intuitive user interface elements, ensuring a great user experience.

## Technologies Used

- TypeScript
- React
- Next.js
- Tailwind CSS
- Shadcn UI
- Clerk Auth
- MongoDB
- Vercel
