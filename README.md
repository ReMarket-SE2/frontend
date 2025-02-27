# ReMarket - Frontend Application

A modern e-commerce marketplace web application built with Next.js, React, and TypeScript.

[![NextJS](https://img.shields.io/badge/NextJS-15.2-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.0-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.0-blue?style=for-the-badge&logo=tailwindcss)](https://tailwindcss.com/)
[![Docker](https://img.shields.io/badge/Docker-Ready-blue?style=for-the-badge&logo=docker)](https://www.docker.com/)

## 📋 Overview

ReMarket is a modern e-commerce marketplace platform that allows users to buy and sell products. This repository contains the frontend application built with Next.js, React, and TypeScript.

## ✨ Features

- **Modern Tech Stack**: Next.js App Router, React 19, TypeScript, and Tailwind CSS
- **Responsive Design**: Fully responsive UI for all device sizes
- **Optimized Performance**: React Server Components and optimized image loading
- **Accessible Components**: Built with Shadcn UI and Radix UI primitives
- **Type-Safe Development**: Full TypeScript support throughout the codebase
- **Containerization**: Docker support for both development and production environments

## 🛠️ Technologies

- **Frontend Framework**: Next.js 15 with App Router
- **UI Library**: React 19
- **Styling**: Tailwind CSS 4.0
- **Component Library**: Shadcn UI with Radix UI primitives
- **Language**: TypeScript 5
- **Package Manager**: pnpm
- **Development Tools**: ESLint, Turbopack
- **Containerization**: Docker and Docker Compose

## 🚀 Getting Started

### Prerequisites

- Node.js 20 or later
- pnpm package manager
- Docker and Docker Compose (optional, for containerized setup)

### Installation

#### Option 1: Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/remarket-frontend.git
   cd remarket-frontend
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Start the development server:
   ```bash
   pnpm dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

#### Option 2: Docker Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/remarket-frontend.git
   cd remarket-frontend
   ```

2. Start the development container:
   ```bash
   docker-compose -f docker/docker-compose.dev.yml up --build
   ```

3. Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

#### Option 3: Docker Production

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/remarket-frontend.git
   cd remarket-frontend
   ```

2. Start the production container:
   ```bash
   docker-compose -f docker/docker-compose.yml up --build
   ```

3. Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## 📁 Project Structure

```
remarket-frontend/
├── app/                # Next.js App Router pages
├── components/         # Reusable UI components
├── docker/             # Docker configuration files
│   ├── Dockerfile      # Production Docker configuration
│   ├── Dockerfile.dev  # Development Docker configuration
│   ├── docker-compose.yml       # Production Docker Compose config
│   └── docker-compose.dev.yml   # Development Docker Compose config
├── lib/                # Utility functions and shared code
├── public/             # Static assets
└── ...
```

## 💻 Development

### Commands

- `pnpm dev`: Start the development server with Turbopack
- `pnpm build`: Build the application for production
- `pnpm start`: Start the production server
- `pnpm lint`: Run ESLint to check code quality

### Docker Commands

- Development:
  ```bash
  docker-compose -f docker/docker-compose.dev.yml up --build
  ```

- Production:
  ```bash
  docker-compose -f docker/docker-compose.yml up --build
  ```

- Stop containers:
  ```bash
  docker-compose -f docker/docker-compose.yml down
  ```

### Coding Standards

This project follows specific coding standards:

- TypeScript for type-safe development
- Functional and declarative programming patterns
- Server components first approach
- Shadcn UI components for consistent UI
- Tailwind CSS for styling

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for more details on how to get started.

## 🧪 Testing

*Testing documentation to be added*

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📚 Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Shadcn UI Documentation](https://ui.shadcn.com/)
- [Radix UI Documentation](https://www.radix-ui.com/)
- [Docker Documentation](https://docs.docker.com/)
