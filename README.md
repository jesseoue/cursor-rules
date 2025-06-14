# Comprehensive Cursor Rules for Modern Web Development

A complete collection of production-ready cursor rules for building modern web applications. These rules are written in MDC format with proper metadata headers and auto-attachment patterns to enhance your development experience in Cursor.

## 🎯 Overview

This repository contains **19 comprehensive cursor rules** covering the complete modern web development stack, from frontend frameworks to backend services, databases, authentication, payments, and more.

## 📁 Available Rules

### Core Frameworks & Languages
- **`typescript.mdc`** - Strict TypeScript configuration, advanced patterns, and utility types
- **`nextjs.mdc`** - Next.js App Router, Server Components, API routes, and performance optimization
- **`react.mdc`** - Modern React patterns, hooks, context, and performance optimization

### Styling & UI
- **`tailwind.mdc`** - Utility-first CSS framework with responsive design patterns
- **`shadcn.mdc`** - Component library with theming and accessibility
- **`framer-motion.mdc`** - Animation library with gestures, transitions, and performance

### Form Handling & Validation
- **`react-hook-form.mdc`** - Form handling with validation and performance optimization
- **`zod.mdc`** - Schema validation with type safety and error handling

### Data Fetching & State Management
- **`tanstack-query.mdc`** - Data synchronization, caching, and mutations
- **`supabase.mdc`** - Backend-as-a-service with real-time features and authentication

### Database & ORM
- **`drizzle.mdc`** - Type-safe SQL ORM with migrations and advanced queries

### Authentication
- **`clerk.mdc`** - Complete authentication solution with organizations and webhooks
- **`better-auth.mdc`** - Modern authentication with session management

### Backend & Automation
- **`inngest.mdc`** - Event-driven functions and background jobs
- **`trigger.mdc`** - Workflow automation and job processing
- **`cloudflare-workers.mdc`** - Edge computing with KV, D1, and R2 storage

### Analytics & Data
- **`tinybird.mdc`** - Real-time analytics with ClickHouse and API endpoints

### Payments & Commerce
- **`stripe.mdc`** - Payment processing, subscriptions, webhooks, and marketplace features

### Development Tools
- **`mcps.mdc`** - Model Context Protocols for enhanced AI development

## 🚀 Quick Start

1. Clone this repository to your local machine
2. Copy the `.cursor/rules/` directory to your project
3. The rules will automatically attach based on file patterns in your project

```bash
git clone https://github.com/jesseoue/cursor-rules.git
cp -r cursor-rules/.cursor /path/to/your/project/
```

## 📖 Rule Types

### Always Rules
- **TypeScript** - Always included for type safety

### Auto-Attached Rules
Most rules auto-attach based on file patterns:
- React components (`.tsx`, `.jsx`)
- API routes (`/api/**`)
- Database schemas (`schema.ts`, `drizzle.config.ts`)
- Configuration files (`tailwind.config.js`, etc.)

### Agent Requested Rules
- **MCPs** - Available when the AI needs protocol information

## 🛠 Features

### ✅ Production Ready
- Battle-tested patterns and best practices
- Security considerations and error handling
- Performance optimization guidelines

### ✅ Type Safe
- Full TypeScript support with proper type definitions
- Zod schema validation patterns
- Type-safe database operations

### ✅ Modern Stack
- Latest framework versions and patterns
- Server Components and App Router
- Edge computing and real-time features

### ✅ Comprehensive Examples
- Complete code examples for every pattern
- Integration examples between services
- Testing strategies and utilities

## 📦 Template Package.json

Includes a complete `package.json.template` with all necessary dependencies for modern web development:

- **Frameworks**: Next.js, React
- **Styling**: Tailwind CSS, Shadcn/ui
- **Forms**: React Hook Form, Zod validation
- **Data**: Tanstack Query, Drizzle ORM
- **Auth**: Clerk, Better Auth
- **Payments**: Stripe
- **Analytics**: Tinybird
- **Animation**: Framer Motion
- **Backend**: Supabase, Inngest, Trigger.dev
- **Development**: TypeScript, ESLint, Prettier

## 🎨 Best Practices Included

- **Performance**: Optimization patterns for React, Next.js, and animations
- **Security**: Authentication, authorization, and data validation
- **Accessibility**: ARIA attributes, keyboard navigation, and screen readers
- **Testing**: Unit tests, integration tests, and E2E testing strategies
- **Error Handling**: Comprehensive error boundaries and user feedback
- **Type Safety**: Strict TypeScript patterns and validation schemas

## 🌟 Why These Rules?

1. **Comprehensive Coverage** - Everything you need for modern web development
2. **Production Tested** - Patterns used in real-world applications
3. **Performance Focused** - Optimization best practices throughout
4. **Developer Experience** - Enhanced autocomplete and intelligent suggestions
5. **Maintainable Code** - Consistent patterns and clean architecture

## 🤝 Contributing

Feel free to submit issues and enhancement requests! These rules are designed to evolve with the modern web development landscape.

## 📄 License

MIT License - feel free to use these rules in your projects!

---

**Happy coding with enhanced AI assistance!** 🚀 