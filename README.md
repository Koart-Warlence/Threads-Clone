# Threads Clone

**Threads Clone** is a project inspired by Threads, designed to familiarize users with Next.js 13, TypeScript, shadcn/ui, MongoDB, and third-party authentication services Clerk and Vercel. Threads Clone provides a complete frontend and backend implementation using the latest technologies and tools. This README.md file will provide an overview of the project, installation guide, feature list, and related resources.

## Key Features

- **User Registration and Login:** Secure user registration and login functionality using Clerk and third-party authentication services.
- **Topics and Threads:** Users can create topics and post threads within topics. Threads support text, images, and links.
- **Comments and Replies:** Users can leave comments on threads and reply to comments.
- **Profile Editing:** Users can edit their profiles, including avatars and personal bios.
- **Clean User Interface:** Utilizes shadcn/ui for clean, intuitive user interface elements, ensuring a great user experience.

## Technology Stack

- **Frontend Framework:** Next.js 13 and TypeScript for building dynamic, modern user interfaces.
- **UI Library:** Uses shadcn/ui to provide aesthetically pleasing interface elements and layouts.
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
   NEXT_PUBLIC_CLERK_FRONTEND_API=https://your-clerk-frontend-api-url
   NEXT_PUBLIC_MONGODB_URI=mongodb://localhost:27017/threads-clone
   ```

   Replace `NEXT_PUBLIC_CLERK_FRONTEND_API` with your Clerk frontend API URL and `NEXT_PUBLIC_MONGODB_URI` with your MongoDB connection string.

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
