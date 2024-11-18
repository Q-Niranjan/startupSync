# StartupSync - Next.js 15 Startup Pitch Platform

## Introduction

StartupSync is a platform built with Next.js 15, where entrepreneurs can submit their startup ideas for virtual pitch competitions, browse other pitches, and gain exposure through a sleek, minimalistic design that ensures a smooth user experience.

---

## Tech Stack

- **React 19**
- **Next.js 15**
- **Sanity** (Headless CMS)
- **Sentry** (Error tracking)
- **TailwindCSS** (Utility-first CSS framework)
- **ShadCN** (UI components)
- **TypeScript** (Static type-checking)

---

## Features

- **Live Content API**: Dynamically displays the latest startup ideas on the homepage using Sanity's Content API.
- **GitHub Authentication**: Simple login via GitHub account.
- **Pitch Submission**: Users can submit their startup ideas, including a title, description, category, and media (image/video).
- **Browse Pitches**: Explore and filter startup ideas by category.
- **Pitch Details**: View details of any pitch, including multimedia content and descriptions.
- **Profile Page**: See and manage the list of pitches users have submitted.
- **Editor Picks**: Admins can highlight top ideas through the "Editor Picks" feature in Sanity Studio.
- **Views Counter**: Tracks the number of views for each pitch instead of an upvote system.
- **Search**: Efficient search functionality to find and view pitches.
- **Minimalistic Design**: Clean UI with a focus on simplicity and ease of use.
- And many more features leveraging **React 19**, **Next.js 15**, and **Sanity** for efficient code architecture and reusability.

---

## 🤸 Quick Start

Follow the steps below to set up the project locally.

### Prerequisites

Ensure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Cloning the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/Q-Niranjan/startupSync.git
cd startupSync
```
### Installation

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_SANITY_PROJECT_ID=
NEXT_PUBLIC_SANITY_DATASET=
NEXT_PUBLIC_SANITY_API_VERSION='vX'
SANITY_TOKEN=

AUTH_SECRET= 
AUTH_GITHUB_ID=
AUTH_GITHUB_SECRET=
```

Replace the placeholder values with your actual Sanity credentials. You can obtain these credentials by signing up &
creating a new project on the [Sanity website](https://www.sanity.io/).

**Running the Project**

```bash
npm run dev
```
***Thank you for exploring StartupSync! We hope it helps entrepreneurs showcase their ideas and grow their startups. Feel free to reach out with questions or suggestions. - Happy coding!***
