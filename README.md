# Comprehensive Cursor Rules for Modern Web Development

A complete collection of **31 production-ready cursor rules** for building modern web applications. These rules are written in MDC format with proper metadata headers and auto-attachment patterns to enhance your development experience in Cursor.

## 🎯 Overview

This repository contains comprehensive cursor rules covering the complete modern web development stack, from core development practices to frontend frameworks, backend services, databases, authentication, payments, and more.

## 📁 Available Rules (31 Total)

### 🧭 Meta & Development Guidelines
- **`_meta-guide.mdc`** - Guide for writing effective cursor rules with proper structure
- **`direct-tone.mdc`** - Communication style for direct, efficient AI responses
- **`auto-commit.mdc`** - Git commit conventions and best practices

### 🏗️ Core Frameworks & Languages
- **`typescript.mdc`** - Strict TypeScript configuration, advanced patterns, and utility types
- **`nextjs.mdc`** - Next.js App Router, Server Components, API routes, and performance optimization
- **`react.mdc`** - Modern React patterns, hooks, context, and performance optimization

### 🎨 Styling & UI
- **`tailwind.mdc`** - Utility-first CSS framework with responsive design patterns
- **`shadcn.mdc`** - Component library with theming and accessibility
- **`framer-motion.mdc`** - Animation library with gestures, transitions, and performance

### 📝 Form Handling & Validation
- **`react-hook-form.mdc`** - Form handling with validation and performance optimization
- **`zod-v4.mdc`** - Modern Zod v4 schema validation with type inference

### 🔄 Data Fetching & State Management
- **`tanstack-query.mdc`** - Data synchronization, caching, and mutations
- **`supabase.mdc`** - Backend-as-a-service with real-time features and authentication

### 🗄️ Database & ORM
- **`drizzle.mdc`** - Type-safe SQL ORM with migrations and advanced queries

### 🔐 Authentication
- **`clerk.mdc`** - Complete authentication solution with organizations and webhooks
- **`better-auth.mdc`** - Modern authentication with session management

### 🚀 Backend & Automation
- **`inngest.mdc`** - Event-driven functions and background jobs
- **`trigger.mdc`** - Workflow automation and job processing
- **`cloudflare-workers.mdc`** - Edge computing with KV, D1, and R2 storage

### 📊 Analytics & Data
- **`tinybird.mdc`** - Real-time analytics with ClickHouse and API endpoints

### 💳 Payments & Commerce
- **`stripe.mdc`** - Payment processing, subscriptions, webhooks, and marketplace features

### 🛠️ Development Tools
- **`mcps.mdc`** - Model Context Protocols for enhanced AI development

### 🔧 Code Quality & Architecture
- **`api-design.mdc`** - RESTful API design standards and best practices
- **`testing-strategy.mdc`** - Comprehensive testing practices (unit, integration, E2E)
- **`dependency-injection.mdc`** - DI patterns and IoC container usage
- **`naming-conventions.mdc`** - Consistent naming for variables, functions, classes
- **`import-ordering.mdc`** - Standards for organizing import statements
- **`comment-style.mdc`** - Code commenting and documentation practices
- **`error-messages.mdc`** - Guidelines for clear, actionable error messages
- **`async-error-handling.mdc`** - Best practices for async/await error handling

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
- 31 specialized rules covering all aspects of development
- Code quality and architecture guidelines
- Testing strategies from unit to E2E
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

1. **Comprehensive Coverage** - 31 rules covering every aspect of modern web development
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