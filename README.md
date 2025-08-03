# Notion-Clone-Advanced-Note-Taking-App

# Fullstack Notion Clone (Lavender-Advanced-Note-Taking-App) : Next.js 13, React, Convex, Tailwind | Full Course 2023

## This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Note that WE followed "Code With Antonio" YT tutorial for reference to Create this project

Key Features:

- Real-time database  🔗 
- Notion-style editor 📝 
- Light and Dark mode 🌓
- Infinite children documents 🌲
- Trash can & soft delete 🗑️
- Authentication 🔐 
- File upload
- File deletion
- File replacement
- Icons for each document (changes in real-time) 🌠
- Expandable sidebar ➡️🔀⬅️
- Full mobile responsiveness 📱
- Publish your note to the web 🌐
- Fully collapsable sidebar ↕️
- Landing page 🛬
- Cover image of each document 🖼️
- Recover deleted files 🔄📄

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/Xp538/Lavender-Advanced-Note-Taking-App.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=                       for database           using https://www.convex.dev/  1:17:45
NEXT_PUBLIC_CONVEX_URL=                  for database           using https://www.convex.dev/  1:17:45

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=       for authentication     using https://clerk.com/       1:17:45
CLERK_SECRET_KEY=                        for authentication     using https://clerk.com/       1:17:45

EDGE_STORE_ACCESS_KEY=                   for cover image        usign https://edgestore.dev/   6:15:13
EDGE_STORE_SECRET_KEY=                   for cover image        using https://edgestore.dev/   6:15:13
```

Make Sure to Run Convex Function in seperate Terminal, it must be running to use its real time database and auth functions.........

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

Below are some ScreenShots of the Project

