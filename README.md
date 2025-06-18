# Neuralearn

**Neuralearn** is a modern Learning Management System (LMS) SaaS platform built from the ground up with Next.js, Supabase, and Stripe. It enables real-time AI-powered tutoring sessions, voice-based learning interactions, and seamless user experiences across devices. Designed for scale and adaptability, Neuralearn delivers an advanced learning environment with robust authentication, billing, and AI voice agent integration using Vapi.

---

## Tech Stack Overview

- **Next.js**: A full-stack React framework supporting server-side rendering and API routes for efficient and scalable web application development.
- **Supabase**: Open-source backend offering real-time subscriptions, authentication, and PostgreSQL database support.
- **Clerk**: Manages user authentication, authorization, and subscriptions with embeddable UIs and flexible APIs.
- **Stripe**: Powers the billing system with support for subscription tiers, upgrades, and secure transactions.
- **Tailwind CSS**: Utility-first CSS framework used for creating highly customizable and responsive UIs.
- **shadcn/ui**: Component library combining Tailwind and Radix UI for accessible, production-ready components.
- **Vapi**: Voice AI platform enabling interactive, low-latency tutoring experiences through AI voice agents.
- **TypeScript**: Enhances development with static typing for greater maintainability and reduced runtime errors.
- **Zod**: Provides schema validation to ensure data correctness and robustness during development.
- **Sentry**: Integrated error and performance monitoring for identifying and resolving issues quickly.

---

## Key Features

- **AI Voice Tutoring**: Engage with AI-powered tutors trained in various subjects for interactive, voice-driven sessions.
- **Secure Authentication**: Sign-up and login using Clerk, including social logins like Google.
- **Subscription Management**: Manage user access and billing through flexible subscription plans with Stripe.
- **Tutor Creation**: Users can create custom AI tutors by selecting subjects, conversation styles, and topics.
- **Bookmarking & History**: Organize and revisit past sessions and favorite tutors.
- **Responsive Design**: Optimized for all screen sizes with a mobile-first approach.
- **Search & Filters**: Easily find tutors with advanced search and filtering options.
- **Code Reusability**: Built with a modular structure to ensure maintainability and scalability.
- **Real-time Sync**: Supabase enables real-time data updates and user collaboration.

---

## Getting Started

### Prerequisites

Ensure the following tools are installed:

- Git
- Node.js
- npm

### Clone the Repository

```bash
git clone https://github.com/adrianhajdin/saas-app.git
cd saas-app
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory and populate it with your environment credentials:

```bash
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

You’ll need to retrieve these keys by setting up accounts with [Clerk](https://clerk.dev), [Supabase](https://supabase.com), [Stripe](https://stripe.com), [Vapi](https://vapi.ai), and [Sentry](https://sentry.io).

### Start the Development Server

```bash
npm run dev
```

Visit `http://localhost:3000` to view the application in your browser.

---

## Contributing

Contributions are welcome. Please open issues or submit pull requests for improvements, bug fixes, or new features.

---

## License

This project is open-source and available under the [MIT License](LICENSE).