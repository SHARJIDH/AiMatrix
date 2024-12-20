# AiMatrix - AI-Powered Solution Platform

AiMatrix is a modern AI-powered platform built with Next.js, leveraging Google's Gemini AI to provide intelligent solutions and automation.

## Features

- Powered by Google's Gemini AI
- Built with Next.js 14
- Modern and responsive UI
- Secure authentication with Clerk
- PostgreSQL database with Drizzle ORM
- Rich text editing capabilities
- Dark/Light mode support

## Tech Stack

- Next.js
- TypeScript
- Tailwind CSS
- Clerk Authentication
- Google Gemini AI
- PostgreSQL
- Drizzle ORM
- Redis for caching

## Getting Started

1. Clone the repository
2. Install dependencies with `npm install`
3. Set up environment variables
4. Run the development server with `npm run dev`

## Environment Variables

Create a `.env` file with the following:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_GOOGLE_GEMINI_API_KEY=
NEXT_PUBLIC_DRIZZLE_DB_URL=
UPSTASH_REDIS_REST_URL=
UPSTASH_REDIS_REST_TOKEN=