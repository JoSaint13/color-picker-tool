# ChromaFlow

> Empower creators with intelligent, intuitive color management

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/user/chromaflow)

## Overview

ChromaFlow is a cross-platform color selection tool designed to simplify design workflows and enhance creative decision-making for UI/UX designers, freelance creatives, and small business professionals.

## Features

- ✨ AI-powered color recommendations
- 🚀 Design system color palette generation
- 💡 Accessibility color contrast checking
- 🔒 Secure user authentication and color palette saving

## Tech Stack

**Frontend:**
- React 18 with TypeScript
- Vite 5.x
- Tailwind CSS
- Zustand State Management
- Color.js & Chroma.js

**Backend:**
- Node.js 20 LTS
- Next.js API Routes
- PostgreSQL with Prisma ORM
- NextAuth.js Authentication

**Deployment:**
- Vercel
- Supabase
- Cloudinary

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/chromaflow.git

# Install dependencies
cd chromaflow
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the application.

## Project Structure

```
/
├── src/
│   ├── components/     # React UI components
│   ├── pages/          # Next.js pages
│   ├── utils/          # Color utility functions
│   ├── hooks/          # Custom React hooks
│   └── styles/         # Tailwind CSS
├── public/             # Static assets
├── tests/              # Test files
└── docs/               # Documentation
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Build for production
npm run test        # Run tests
npm run lint        # Lint code
```

### Environment Variables

Required environment variables:

```env
NEXT_PUBLIC_API_URL=your-api-url
DATABASE_URL=your-postgres-connection-string
NEXTAUTH_SECRET=your-authentication-secret
```

## Testing

```bash
# Run unit tests
npm run test

# Run with coverage
npm run test:coverage

# Run E2E tests
npm run test:e2e
```

## Deployment

### Vercel (Recommended)

```bash
npm run build
vercel --prod
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/color-enhancement`)
3. Commit your changes (`git commit -m 'Add AI color recommendation'`)
4. Push to the branch (`git push origin feature/color-enhancement`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, email support@chromaflow.com or open a GitHub issue.

---

**Generated with ❤️ by ChromaFlow Team**