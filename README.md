# Comprehensive Cursor Rules for Modern Web Development (2025 Edition)

A complete collection of **59+ production-ready cursor rules** organized into **10 logical categories** and updated with the **latest 2025 features** for building modern web applications. These rules are written in MDC format with proper metadata headers and auto-attachment patterns to enhance your development experience in Cursor.

## 🎯 Overview

This repository contains comprehensive cursor rules covering the complete modern web development stack, from core development practices to frontend frameworks, backend services, databases, authentication, payments, and more. **All major frameworks have been updated with 2025 features including Next.js 15/16, React 19.2, TypeScript 5.8, Tailwind v4, TanStack Query v5, Zod v4, Drizzle ORM, and Vercel.**

## ✨ Latest Updates (2025)

### Core Frameworks
- **Next.js 15/16**: React 19 support, Turbopack stable, Cache Components, unstable_after API
- **React 19.2**: useActionState, useFormStatus, useOptimistic, useEffectEvent, Activity component
- **TypeScript 5.8**: Improved control flow, ES2024 support, faster builds, new compiler options
- **Bun 1.3+**: 7× faster package manager, native TypeScript, built-in test runner, Bun.SQL

### Styling & UI
- **Tailwind CSS v4**: 5x faster builds, CSS-first config, container queries, oklch colors
- **Radix UI**: Accessible primitives, single package, cookie support, WebSocket compression

### Data & ORMs
- **TanStack Query v5**: Suspense hooks, queryOptions helper, useMutationState, 20% smaller
- **Zod v4**: 14x faster parsing, @zod/mini, global registry, custom metadata, pretty errors
- **Drizzle ORM 0.44+**: Identity columns, $onUpdate, read replicas, set operators
- **Prisma ORM 6.16+**: Rust-free (90% smaller), omit API, multi-schema, 3.4× faster

### Testing & Quality
- **Vitest 4.0**: Visual regression, browser mode, viewport matcher, line number filtering
- **Playwright 2025**: AI-powered testing with MCP, auto-assertions, enhanced debugging

### Backend & APIs
- **tRPC v11**: Server-Sent Events, non-JSON content types, improved RSC support
- **Resend**: React Email integration, batch sending, webhooks, high deliverability
- **Uploadthing**: Type-safe uploads, automatic optimizations, progress tracking
- **Upstash Redis**: Serverless, edge-compatible, rate limiting with @upstash/ratelimit

### Cloudflare Platform (New - 2025)
- **D1 Database**: Global read replication, SQLite, time travel, session consistency
- **R2 Storage**: S3-compatible, zero egress fees, automatic region selection
- **Durable Objects**: Stateful serverless, SQLite storage (GA), WebSockets, free tier
- **Workers AI**: 2-4× faster inference, Llama 4 Scout, batch API, 180+ cities

### Platform & Deployment
- **Vercel 2025**: Rolling Releases, Fluid Compute, AI Gateway, 300ms global propagation
- **Turborepo**: Remote caching, parallel execution, task pipelines, incremental builds

## 📁 Organized Rule Structure (59+ Total)

All rules are now organized into **10 logical directories** for easy navigation:

### 📂 `.cursor/rules/frameworks/` (4 files)
Core development frameworks and languages
- **`typescript.mdc`** - TypeScript 5.8: Improved control flow, ES2024, faster performance
- **`nextjs.mdc`** - Next.js 15/16: React 19, Turbopack, Cache Components, PPR
- **`react.mdc`** - React 19.2: New hooks, Actions API, Server Components
- **`bun.mdc`** - Bun 1.3+: Fast runtime, package manager, test runner, bundler

### 📂 `.cursor/rules/styling/` (4 files)
CSS frameworks and animation libraries
- **`tailwind.mdc`** - Tailwind v4: 5x faster, CSS-first config, container queries
- **`shadcn.mdc`** - Component library with theming and accessibility
- **`framer-motion.mdc`** - Animation library with gestures and transitions
- **`radix-ui.mdc`** - Radix UI Primitives: Accessible, unstyled components

### 📂 `.cursor/rules/validation/` (2 files)
Form handling and schema validation
- **`zod-v4.mdc`** - Zod v4: 14x faster, @zod/mini, global registry, metadata
- **`react-hook-form.mdc`** - Form handling with validation and optimization

### 📂 `.cursor/rules/data/` (7 files)
Data fetching, state management, and databases
- **`tanstack-query.mdc`** - TanStack Query v5: Suspense hooks, queryOptions
- **`drizzle.mdc`** - Drizzle ORM 0.44+: Identity columns, $onUpdate, read replicas
- **`prisma.mdc`** - Prisma ORM 6.16+: Rust-free, omit API, multi-schema, 3.4× faster
- **`supabase.mdc`** - Backend-as-a-service with real-time features
- **`convex.mdc`** - Real-time backend with TypeScript
- **`cloudflare-d1.mdc`** - Cloudflare D1: Serverless SQL with global read replication
- **`cloudflare-r2.mdc`** - Cloudflare R2: S3-compatible storage with zero egress

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

### 📂 `.cursor/rules/backend/` (12 files)
Backend services, APIs, and automation
- **`inngest.mdc`** - Event-driven functions and background jobs
- **`trigger.mdc`** - Trigger.dev v3: Workflow automation
- **`triggerdev.mdc`** - Trigger.dev platform integration
- **`tinybird.mdc`** - Real-time analytics with ClickHouse
- **`stripe.mdc`** - Payment processing and subscriptions
- **`qstash.mdc`** - Message queue and scheduling
- **`trpc.mdc`** - tRPC v11: Type-safe APIs with SSE subscriptions
- **`resend.mdc`** - Resend email API with React Email integration
- **`uploadthing.mdc`** - UploadThing: Type-safe file uploads for Next.js
- **`upstash-redis.mdc`** - Upstash Redis: Serverless, edge-compatible data store
- **`cloudflare-durable-objects.mdc`** - Cloudflare Durable Objects: Stateful serverless with SQLite
- **`cloudflare-workers-ai.mdc`** - Cloudflare Workers AI: GPU inference across 180+ cities

### 📂 `.cursor/rules/quality/` (7 files)
Testing, security, performance, and accessibility
- **`testing-strategy.mdc`** - Comprehensive testing (unit, integration, E2E)
- **`vitest.mdc`** - Vitest 4.0: Visual regression, browser mode, enhanced reporting
- **`playwright.mdc`** - Playwright 2025: AI-powered testing with MCP integration
- **`security.mdc`** - Web application security and OWASP guidelines
- **`performance.mdc`** - Performance optimization techniques
- **`accessibility.mdc`** - Web accessibility (WCAG compliance)
- **`seo.mdc`** - SEO optimization for Next.js

### 📂 `.cursor/rules/conventions/` (10 files)
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
- **`turborepo.mdc`** - Turborepo: Monorepo build system with remote caching

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
- 59+ specialized rules covering all aspects of development
- Code quality and architecture guidelines
- Security, performance, and accessibility standards
- Testing strategies from unit to E2E with AI-powered tools
- SEO optimization and project organization
- API design and error handling standards
- Modern ORMs, testing frameworks, and backend services
- Complete Cloudflare platform (D1, R2, Durable Objects, Workers AI)

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

1. **Comprehensive Coverage** - 59+ rules covering every aspect of modern web development
2. **Production Tested** - Patterns used in real-world applications
3. **Performance Focused** - Optimization best practices throughout
4. **Developer Experience** - Enhanced autocomplete and intelligent suggestions
5. **Modern & Updated** - Latest 2025 framework versions and current best practices
6. **Quality Focused** - Code quality, testing, and architecture guidelines
7. **AI-Powered Testing** - Latest Vitest 4.0 and Playwright with MCP integration
8. **Modern ORMs** - Prisma 6.16+ and Drizzle with latest optimizations
9. **Complete Cloudflare** - D1, R2, Durable Objects, and Workers AI with 2025 features

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