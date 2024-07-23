# Jasbook

Welcome to Jasbook, a full-stack social media application built with modern technologies to deliver an exceptional user experience. This app includes features like infinite loading, optimistic updates, authentication, direct messaging, notifications, file uploads, and much more.

## Features

- **Next.js 15**

  - Server actions and server components

- **TanStack React Query**

  - Optimistic updates

- **User Experience**

  - Infinite scrolling feeds
  - File uploads with drag & drop and copy-paste support (UploadThing)
  - Like system
  - Follow system
  - Comment system
  - Notification system
  - Direct messaging system (powered by Stream)
  - Bookmarks

- **Authentication**

  - Lucia authentication (username/password & Google OAuth2)

- **Database**

  - Postgres DB with Prisma ORM

- **Social Media Features**

  - Hashtags & mentions
  - Full-text search

- **Performance**

  - Advanced caching & revalidation

- **Design**

  - Mobile-responsive layout with Tailwind CSS & Shadcn UI components
  - Dark theme, light theme, and system theme

- **Form Handling**

  - Real-time form validation with React Hook Form & Zod

- **Rich Text Editing**

  - TipTap editor

- **Deployment**
  - Deploy on Vercel & set up cron job

## Getting Started

Follow these steps to get the app running on your local machine:

1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/3tared/jasbook.git
   cd jasbook
   \`\`\`

2. **Install dependencies:**
   \`\`\`bash
   npm install
   \`\`\`

3. **Set up environment variables:**
   Create a \`.env.local\` file in the root directory and add your environment variables. Refer to \`.env.example\` for the required variables.

4. **Run database migrations:**
   \`\`\`bash
   npx prisma migrate dev
   \`\`\`

5. **Start the development server:**
   \`\`\`bash
   npm run dev
   \`\`\`

   Your app should now be running on [http://localhost:3000](http://localhost:3000).

## Technologies Used

- **Frontend:**

  - Next.js 15
  - TanStack React Query
  - Tailwind CSS
  - Shadcn UI components
  - TipTap editor

- **Backend:**

  - Next.js server actions and server components
  - Postgres DB with Prisma ORM
  - Lucia authentication
  - Stream for direct messaging

- **Others:**
  - UploadThing for file uploads
  - React Hook Form & Zod for form validation

## Acknowledgements

Special thanks to all the libraries and tools that made this project possible.
