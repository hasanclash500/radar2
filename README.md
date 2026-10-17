# Radar2 / Divsaz

A Persian-language real-estate listing and management web application built with React, TypeScript, Vite, Tailwind CSS, and Convex.

## Requirements

- Bun (recommended; `bun.lock` is included)
- A Convex account for backend features

## Local development

1. Install dependencies: `bun install`
2. Copy `.env.example` to `.env.local` and fill in the required values.
3. Start the Convex development deployment: `npx convex dev`
4. In another terminal, start Vite: `bun run dev`

See [`SETUP-FA.md`](SETUP-FA.md) for the full Persian setup and deployment guide.

## Build and tests

- `bun run build` — type-check and build the app
- `bun run seo:test` — run sitemap tests
- `bun run seo:audit` — run SEO audit

## Environment and security

Never commit `.env.local`, deployment keys, API tokens, or production secrets. Use `.env.example` as a template and configure secrets in your deployment provider.

## Notes

The application needs its own Convex deployment and environment variables before backend-powered features will work. See `.env.example` and `SETUP-FA.md`.
