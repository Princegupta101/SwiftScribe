# SwiftScribe - The SaaS for Students

SwiftScribe is a SaaS (Software as a Service) platform designed to enhance student productivity and streamline academic tasks. With SwiftScribe, students can efficiently manage their study materials, collaborate with peers, and access powerful AI-driven features for academic assistance.

## Tech Stack

- React JS
- Next JS
- Typescript
- Tailwind CSS
- Vercel
- PostgreSQL

## Features

- **PDF Upload**: Easily upload PDF files for storage and organization within the application.
- **AI Assistance**: Access powerful AI-driven features for academic assistance, including text summarization, question answering, and more.
- **Collaboration**: Collaborate with peers by sharing study materials, notes, and insights.
- **Dashboard**: Get an overview of your study progress, upcoming deadlines, and personalized recommendations.
- **Billing Integration**: Seamlessly integrate billing functionality for subscription plans and payments.
- **Responsive Design**: Enjoy a seamless experience across devices with a responsive and user-friendly design.


## Getting Started

1. **Prerequisites**: Ensure that **Git** and **NodeJS** are installed on your system.
2. **Clone the Repository**: Clone this repository to your local computer.
3. **Set up Environment Variables**: Create a `.env` file in the root directory and populate it with the required environment variables as described below.

### Environment Variables

```env
# .env

# Disable Next.js telemetry
NEXT_TELEMETRY_DISABLED=1

# Kinde keys and URLs
KINDE_CLIENT_ID=XXXXXXXXXXXXXXXXXXXXXXXXXXX
KINDE_CLIENT_SECRET=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
KINDE_ISSUER_URL=https://example.kinde.com
KINDE_SITE_URL=http://localhost:3000
KINDE_POST_LOGOUT_REDIRECT_URL=http://localhost:3000
KINDE_POST_LOGIN_REDIRECT_URL=http://localhost:3000/dashboard

# Neon DB URI
DATABASE_URL="postgresql://<user>:<password>@<hostname>:<port>/swiftscribe?sslmode=require"

# Uploadthing API key and app ID
UPLOADTHING_SECRET=sk_live_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
UPLOADTHING_APP_ID=xxxxxxxxxxx

# App base URL
NEXT_PUBLIC_BASE_URL=http://localhost:3000

# Pinecone API key
PINECONE_API_KEY=xxxxxxxxxx-xxxxx-xxxx-xxxxxx-xxxxxxxxxxx

# OpenAI API key
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

# Stripe secret key, price ID, and webhook secret
STRIPE_SECRET_KEY=sk_test_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
STRIPE_PRICE_ID=price_XXXXXXXXXXXXXXXXXXXXXXXXX
STRIPE_WEBHOOK_SECRET=whsec_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX