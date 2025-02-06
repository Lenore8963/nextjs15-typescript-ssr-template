# Next.js 15 TypeScript SSR Template for AWS Amplify

A production-ready template for Next.js 15 applications with TypeScript and SSR support, designed for deployment to AWS Amplify.

## Features

- Next.js 15 with App Router
- TypeScript configuration
- SSR support
- Tailwind CSS
- ESLint configuration
- Deployment-ready for AWS Amplify

## Quick Start

1. Clone this repository
   \```bash
   git clone https://github.com/[your-username]/nextjs15-typescript-ssr-template.git
   cd nextjs15-typescript-ssr-template
   \```

2. Install dependencies
   \```bash
   npm install
   \```

3. Start development server
   \```bash
   npm run dev
   \```

## Key Files and Directories

- `app/`: Main application directory using Next.js 15 App Router
  - `layout.tsx`: Root layout component
  - `page.tsx`: Home page component
- `public/`: Static files like images
- `styles/`: CSS files including global styles
- `components/`: Reusable React components
- `lib/`: Utility functions and shared logic
- `types/`: TypeScript type definitions
- `amplify.yml`: AWS Amplify deployment configuration
- `next.config.js`: Next.js configuration file
- `package.json`: Project dependencies and scripts

## Deployment to AWS Amplify

This template is designed to work with the aws-amplify-nextjs-cdk-template repository. To deploy:

1. Push your code to GitHub
2. Follow the instructions in aws-amplify-nextjs-cdk-template
3. No additional configuration needed!

## Common Issues and Solutions

### Build Failures in Amplify

- Verify Node.js version matches amplify.yml
- Check for missing dependencies
- Ensure proper baseDirectory in amplify.yml

### SSR Issues

- Verify WEB_COMPUTE platform is enabled in Amplify
- Check for proper Next.js configuration
