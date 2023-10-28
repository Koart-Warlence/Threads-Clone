# Threads Clone

**Threads Clone** is a project inspired by Threads, serves as a prototype imitation designed to familiarize users with Next.js 13, TypeScript, shadcn/ui, MongoDB, and third-party authentication via Clerk. The application is also deployed on Vercel for seamless accessibility and use.

## Key Features

- **User Registration and Login:** Secure user registration and login functionality using Clerk and third-party authentication services.
- **Communities and Threads:** Users can create Communities and post threads within or without Communities.
- **Comments and Replies:** Users can leave comments on threads and reply to comments.
- **Profile Editing:** Users can edit their profiles, including avatars and personal bios.
- **Clean User Interface:** Utilizes shadcn/ui for clean, intuitive user interface elements, ensuring a great user experience.

## Technology Stack

- **Frontend Framework:** Next.js 13 and TypeScript for building dynamic, modern user interfaces.
- **UI Library:** Uses shadcn/ui to provide aesthetically pleasing interface elements and layouts.
- **File Upload:** Incorporates UploadThing for seamless file uploads, allowing users to upload and manage files securely.
- **Database:** MongoDB for storing user information, topics, threads, and comments data.
- **Authentication and Authorization:** Utilizes Clerk for secure user authentication, ensuring only authorized users can access specific pages and functionalities.
- **Deployment:** Hosted on Vercel for fast, stable project deployment and hosting.

## Installation Guide

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/threads-clone.git
   ```

2. Navigate to the project directory:

   ```
   cd threads-clone
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Set up environment variables: Create a `.env.local` file in the project root and configure the following environment variables:

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

   Replace
   `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` with your Clerk Publishable key.
   `CLERK_SECRET_KEY=YOUR_CLERK_SECRET_KEY` with your Clerk Secret key.
   `NEXT_CLERK_WEBHOOK_SECRET` with your Clerk Webhook secret.
   `MONGODB_URL` with your MongoDB connection string.
   `UPLOADTHING_SECRET` with your UploadThing secret.
   `UPLOADTHING_APP_ID` with your UploadThing application ID.

   Make sure to replace these values with the respective actual values.

5. Start the project:

   ```
   npm run dev
   ```

   The project will run at `http://localhost:3000`.

## Contribution Guidelines

If you want to contribute to Threads Clone, follow these steps:

1. Fork this project on GitHub.
2. Create your branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new Pull Request.

## Related Resources

- Next.js Official Website: [https://nextjs.org/](https://nextjs.org/)
- shadcn/ui GitHub Repository: [https://github.com/shadcn/ui](https://github.com/shadcn/ui)
- Clerk Official Website: [https://clerk.dev/](https://clerk.dev/)
- MongoDB Official Website: [https://www.mongodb.com/](https://www.mongodb.com/)
- Vercel Official Website: [https://vercel.com/](https://vercel.com/)

Thank you for using and contributing to Threads Clone! If you have any questions or suggestions, feel free to reach out.
