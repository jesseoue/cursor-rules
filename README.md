# Comprehensive Cursor Rules for Modern Web Development (2025 Edition)

A complete collection of **45+ production-ready cursor rules** organized into **10 logical categories** and updated with the **latest 2025 features** for building modern web applications. These rules are written in MDC format with proper metadata headers and auto-attachment patterns to enhance your development experience in Cursor.

## 🎯 Overview

This repository contains comprehensive cursor rules covering the complete modern web development stack, from core development practices to frontend frameworks, backend services, databases, authentication, payments, and more. **All major frameworks have been updated with 2025 features including Next.js 15/16, React 19.2, TypeScript 5.8, Tailwind v4, TanStack Query v5, Zod v4, Drizzle ORM, and Vercel.**

## ✨ Latest Updates (2025)

### Core Frameworks
- **Next.js 15/16**: React 19 support, Turbopack stable, Cache Components, unstable_after API
- **React 19.2**: useActionState, useFormStatus, useOptimistic, useEffectEvent, Activity component
- **TypeScript 5.8**: Improved control flow, ES2024 support, faster builds, new compiler options

### Styling & Data
- **Tailwind CSS v4**: 5x faster builds, CSS-first config, container queries, oklch colors
- **TanStack Query v5**: Suspense hooks, queryOptions helper, useMutationState, 20% smaller
- **Zod v4**: 14x faster parsing, @zod/mini, global registry, custom metadata, pretty errors
- **Drizzle ORM 0.44+**: Identity columns, $onUpdate, read replicas, set operators

### Platform & Deployment
- **Vercel 2025**: Rolling Releases, Fluid Compute, AI Gateway, 300ms global propagation

## 📁 Organized Rule Structure (45+ Total)

All rules are now organized into **10 logical directories** for easy navigation:

### 📂 `.cursor/rules/frameworks/` (3 files)
Core development frameworks and languages
- **`typescript.mdc`** - TypeScript 5.8: Improved control flow, ES2024, faster performance
- **`nextjs.mdc`** - Next.js 15/16: React 19, Turbopack, Cache Components, PPR
- **`react.mdc`** - React 19.2: New hooks, Actions API, Server Components

### 📂 `.cursor/rules/styling/` (3 files)
CSS frameworks and animation libraries
- **`tailwind.mdc`** - Tailwind v4: 5x faster, CSS-first config, container queries
- **`shadcn.mdc`** - Component library with theming and accessibility
- **`framer-motion.mdc`** - Animation library with gestures and transitions

### 📂 `.cursor/rules/validation/` (2 files)
Form handling and schema validation
- **`zod-v4.mdc`** - Zod v4: 14x faster, @zod/mini, global registry, metadata
- **`react-hook-form.mdc`** - Form handling with validation and optimization

### 📂 `.cursor/rules/data/` (4 files)
Data fetching, state management, and databases
- **`tanstack-query.mdc`** - TanStack Query v5: Suspense hooks, queryOptions
- **`drizzle.mdc`** - Drizzle ORM 0.44+: Identity columns, $onUpdate, read replicas
- **`supabase.mdc`** - Backend-as-a-service with real-time features
- **`convex.mdc`** - Real-time backend with TypeScript

### 📂 `.cursor/rules/auth/` (2 files)
Authentication and user management
- **`clerk.mdc`** - Complete authentication with organizations and webhooks
- **`better-auth.mdc`** - Modern authentication with session management

### 📂 `.cursor/rules/deployment/` (7 files)
Deployment platforms and hosting services
- **`vercel.mdc`** - Vercel 2025: Rolling Releases, Fluid Compute, AI Gateway
- **`netlify.mdc`** - Netlify platform deployment and edge functions
- **`cloudflare.mdc`** - Cloudflare Pages and Workers
- **`cloudflare-workers.mdc`** - Edge computing with KV, D1, R2
- **`railway.mdc`** - Railway app deployment platform
- **`fly-io.mdc`** - Fly.io global app deployment
- **`neon.mdc`** - Neon serverless Postgres

### 📂 `.cursor/rules/backend/` (6 files)
Backend services, APIs, and automation
- **`inngest.mdc`** - Event-driven functions and background jobs
- **`trigger.mdc`** - Trigger.dev v3: Workflow automation
- **`triggerdev.mdc`** - Trigger.dev platform integration
- **`tinybird.mdc`** - Real-time analytics with ClickHouse
- **`stripe.mdc`** - Payment processing and subscriptions
- **`qstash.mdc`** - Message queue and scheduling

### 📂 `.cursor/rules/quality/` (5 files)
Testing, security, performance, and accessibility
- **`testing-strategy.mdc`** - Comprehensive testing (unit, integration, E2E)
- **`security.mdc`** - Web application security and OWASP guidelines
- **`performance.mdc`** - Performance optimization techniques
- **`accessibility.mdc`** - Web accessibility (WCAG compliance)
- **`seo.mdc`** - SEO optimization for Next.js

### 📂 `.cursor/rules/conventions/` (9 files)
Code style, architecture, and best practices
- **`api-design.mdc`** - RESTful API design standards
- **`naming-conventions.mdc`** - Consistent naming patterns
- **`import-ordering.mdc`** - Import statement organization
- **`comment-style.mdc`** - Code documentation practices
- **`error-messages.mdc`** - Clear, actionable error messages
- **`async-error-handling.mdc`** - Async/await error handling
- **`dependency-injection.mdc`** - DI patterns and IoC containers
- **`project-structure.mdc`** - File organization patterns
- **`environment-management.mdc`** - Environment configuration

### 📂 `.cursor/rules/meta/` (4 files)
Meta rules and development guidelines
- **`_meta-guide.mdc`** - Guide for writing cursor rules
- **`direct-tone.mdc`** - Communication style for AI responses
- **`auto-commit.mdc`** - Git commit conventions
- **`mcps.mdc`** - Model Context Protocols

## 🚀 Quick Start

1. Clone this repository to your project root
2. Copy the `.cursor/rules/` directory to your project
3. The rules will automatically attach based on file patterns

```bash
git clone https://github.com/jesseoue/cursor-rules.git
cd your-project
cp -r ../cursor-rules/.cursor .
```

## 📖 Rule Types

### Always Active Rules
- **Direct Tone** - Always active for efficient communication
- **TypeScript** - Always included for type safety

### Auto-Attached Rules
Most rules auto-attach based on file patterns:
- React components (`.tsx`, `.jsx`)
- API routes (`/api/**`, `/routes/**`)
- Database schemas (`schema.ts`, `drizzle.config.ts`)
- Test files (`*.test.ts`, `*.spec.ts`)
- Configuration files (`tailwind.config.js`, etc.)

### Context-Specific Rules
- **Testing Strategy** - Activates in test files and test directories
- **API Design** - Activates in API route files
- **Zod v4** - Activates in TypeScript files for validation

## 🛠 Enhanced Features

### ✅ Production Ready
- Battle-tested patterns and best practices
- Security considerations and error handling
- Performance optimization guidelines
- Modern framework versions and patterns

### ✅ Type Safe & Modern
- Full TypeScript support with proper type definitions
- Zod v4 schema validation patterns
- Type-safe database operations
- Latest Next.js App Router patterns

### ✅ Comprehensive Coverage
- 36 specialized rules covering all aspects of development
- Code quality and architecture guidelines
- Security, performance, and accessibility standards
- Testing strategies from unit to E2E
- SEO optimization and project organization
- API design and error handling standards

### ✅ Developer Experience
- Enhanced autocomplete and intelligent suggestions
- Consistent patterns and clean architecture
- Direct communication style for efficient AI assistance
- Proper rule organization and discovery

## 📦 Template Package.json

Includes a complete `package.json.template` with all necessary dependencies:

- **Frameworks**: Next.js, React, TypeScript
- **Styling**: Tailwind CSS, Shadcn/ui, Framer Motion
- **Forms**: React Hook Form, Zod v4 validation
- **Data**: Tanstack Query, Drizzle ORM, Supabase
- **Auth**: Clerk, Better Auth
- **Payments**: Stripe
- **Backend**: Inngest, Trigger.dev, Cloudflare Workers
- **Analytics**: Tinybird
- **Development**: ESLint, Prettier, Testing frameworks

## 🎨 Best Practices Included

- **Performance**: Optimization patterns for React, Next.js, and animations
- **Security**: Authentication, authorization, and data validation
- **Accessibility**: ARIA attributes, keyboard navigation, and screen readers
- **Testing**: Comprehensive testing strategies and utilities
- **Error Handling**: Clear error messages and async error patterns
- **Code Quality**: Naming conventions, import ordering, and documentation
- **Architecture**: Dependency injection and API design patterns

## 🌟 Why These Rules?

1. **Comprehensive Coverage** - 36 rules covering every aspect of modern web development
2. **Production Tested** - Patterns used in real-world applications
3. **Performance Focused** - Optimization best practices throughout
4. **Developer Experience** - Enhanced autocomplete and intelligent suggestions
5. **Modern & Updated** - Latest framework versions and current best practices
6. **Quality Focused** - Code quality, testing, and architecture guidelines

## 🔧 Writing Your Own Rules

Use the included `_meta-guide.mdc` for guidelines on writing effective cursor rules:

- Simple XML structure for LLM optimization
- Proper frontmatter with descriptions and file patterns
- Focus on essential requirements without over-structuring
- Clear examples and practical guidance

## 🤝 Contributing

Feel free to submit issues and enhancement requests! These rules are designed to evolve with the modern web development landscape.

## 📄 License

MIT License - feel free to use these rules in your projects!

---

**Happy coding with enhanced AI assistance!** 🚀 