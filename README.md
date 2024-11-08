# Podcastr

A modern AI-powered podcast platform that allows users to create and share AI-generated podcasts.

## Features

- 🎙️ AI Voice Generation - Create podcasts using various AI voices
- 🖼️ AI Thumbnail Generation - Generate custom thumbnails for podcasts
- 🎵 Custom Audio Player - Full-featured audio player with controls
- 🔍 Podcast Discovery - Browse and discover trending podcasts
- 👤 User Profiles - Track user's podcasts and activity
- 📱 Responsive Design - Works seamlessly across devices

## Tech Stack

- **Framework:** Next.js 14
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Authentication:** Clerk
- **Database & Backend:** Convex
- **AI Integration:** OpenAI API
- **Audio Processing:** Web Audio API
- **File Storage:** Convex Storage

## Getting Started

### Prerequisites

- Node.js 18+
- npm/yarn
- Convex account
- Clerk account
- OpenAI API key

### Installation

1. Clone the repository

```
git clone git@github.com:Zeyu-Chen/AI-Podcast-App.git
cd podcastr
```

2. Install dependencies

```
npm install
```

3. Set up environment variables

```
NEXT_PUBLIC_CONVEX_URL=your_convex_url
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
CLERK_SECRET_KEY=your_clerk_secret
OPENAI_API_KEY=your_openai_key
```

4. Start the development server

```
npm run dev
```

### Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
OPENAI_API_KEY=
```

## Project Structure

```
podcastr/
├── app/               # Next.js app directory
├── components/        # Reusable components
├── convex/            # Convex backend functions
├── lib/               # Utility functions
├── public/            # Static assets
└── types/             # TypeScript type definitions
```
