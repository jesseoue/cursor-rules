# Cursor Rules Repository

A comprehensive collection of **MDC (Markdown with metadata)** cursor rules for modern web development. These rules provide intelligent code assistance, patterns, and best practices for popular frameworks, tools, and services.

## 🚀 What are Cursor Rules?

Cursor rules are specialized configuration files that enhance the AI coding assistant's understanding of your project. They provide:

- **Context-aware suggestions** based on your tech stack
- **Framework-specific patterns** and best practices  
- **Intelligent auto-completion** for common tasks
- **Code quality enforcement** through established conventions

## 📁 Rule Types

Our rules use Cursor's MDC format with metadata-driven activation:

### Always Active Rules
- **`typescript.mdc`** - Core TypeScript patterns and utilities (always included)

### Auto-Attached Rules  
Automatically activated when working with matching files:

- **`nextjs.mdc`** - Next.js App Router patterns (`**/app/**/*.{ts,tsx}`, `next.config.*`)
- **`react.mdc`** - React component patterns (`**/*.{jsx,tsx}`, `**/components/**`)
- **`drizzle.mdc`** - Database schema and queries (`**/db/**/*.ts`, `drizzle.config.*`) 
- **`shadcn.mdc`** - UI component patterns (`**/components/ui/**`, `components.json`)
- **`clerk.mdc`** - Authentication flows (`**/middleware.{ts,tsx}`, `**/auth/**`)
- **`tinybird.mdc`** - Analytics pipelines (`**/*.pipe`, `**/tinybird/**`)
- **`cloudflare-workers.mdc`** - Edge computing (`**/workers/**`, `wrangler.toml`)

### Agent-Requested Rules
Available when the AI determines they're relevant:

- **`mcps.mdc`** - Model Context Protocols reference guide

## 🛠️ Tech Stack Coverage

### Frontend Frameworks
- **Next.js 15** - App Router, Server Components, API Routes
- **React 18** - Hooks, Performance optimization, Testing patterns
- **TypeScript** - Advanced types, utilities, error handling

### Backend & Database  
- **Drizzle ORM** - Type-safe database operations
- **Cloudflare Workers** - Edge computing, KV, D1, R2
- **Tinybird** - Real-time analytics and data pipelines

### UI & Design
- **Shadcn/ui** - Component library patterns
- **Tailwind CSS** - Utility-first styling
- **Class Variance Authority** - Component variants

### Authentication & Services
- **Clerk** - User management and authentication
- **Model Context Protocols** - AI tool integrations

## 📚 Usage Examples

### Next.js App Router
```typescript
// Automatically provides patterns for:
export default async function Page({ params }: { params: { id: string } }) {
  const data = await getData(params.id)
  return <div>{data.title}</div>
}
```

### Drizzle Schema
```typescript
// Auto-suggests proper table definitions:
export const users = pgTable('users', {
  id: uuid('id').defaultRandom().primaryKey(),
  email: varchar('email', { length: 255 }).notNull().unique(),
  createdAt: timestamp('created_at').defaultNow(),
})
```

### Tinybird Analytics
```sql
-- Provides pipe patterns and SQL optimizations:
SELECT 
  toDate(timestamp) as date,
  count() as events
FROM analytics_events
WHERE timestamp >= now() - interval 30 day
GROUP BY date
ORDER BY date DESC
```

## 🎯 Key Features

- **🔄 Auto-activation** based on file patterns
- **📖 Comprehensive examples** for each technology
- **⚡ Performance patterns** and optimizations  
- **🛡️ Security best practices** built-in
- **🧪 Testing strategies** included
- **📱 TypeScript-first** approach throughout

## 🔧 Installation

1. **Clone this repository** to your preferred location:
   ```bash
   git clone https://github.com/your-username/cursor-rules.git
   ```

2. **Copy relevant rules** to your project's `.cursor/rules/` directory:
   ```bash
   cp cursor-rules/.cursor/rules/*.mdc your-project/.cursor/rules/
   ```

3. **Rules activate automatically** when you open matching files in Cursor

## 💡 Contributing

We welcome contributions! To add new rules or improve existing ones:

1. Fork the repository
2. Create MDC files with proper metadata headers
3. Follow the established patterns and best practices
4. Submit a pull request with clear descriptions

### Rule Format
```markdown
---
rule_type: auto_attached
title: Your Technology Rules  
description: Brief description of what this rule covers
patterns: ["**/*.ext", "**/config.*"]
---

# Your Technology Rules

## Setup & Configuration
...
```

## 📖 Documentation

Each rule file contains:
- **Setup instructions** and configuration
- **Code patterns** and examples  
- **Best practices** and conventions
- **Performance optimizations**
- **Security considerations**
- **Testing approaches**

## 🚀 What's Included

### Framework Rules
- Next.js 15 App Router patterns
- React 18 component patterns  
- TypeScript advanced patterns

### Database Rules
- Drizzle ORM schema definitions
- Query optimization patterns
- Migration strategies

### UI Rules  
- Shadcn/ui component patterns
- Tailwind CSS utilities
- Responsive design patterns

### Backend Rules
- Cloudflare Workers edge functions
- Tinybird analytics pipelines
- Authentication flows

### Tool Integration
- Model Context Protocols
- Development workflows
- Deployment strategies

## 🎉 Benefits

- **Faster development** with intelligent suggestions
- **Consistent code quality** across your team
- **Framework best practices** automatically applied
- **Reduced boilerplate** through smart templates
- **Performance optimizations** built into suggestions

---

**Ready to supercharge your development workflow?** Start using these cursor rules today and experience the power of AI-assisted coding with deep framework knowledge! 🚀 