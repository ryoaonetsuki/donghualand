# Donghua Platform

A Chinese animation streaming platform built with Hono, TypeScript, Vite, Cloudflare Pages, and D1.

## Requirements

- Node.js
- npm
- Cloudflare account for deployment
- Wrangler for Cloudflare commands

## Installation

```bash
git clone https://github.com/ryoaonetsuki/donghualand.git
cd donghualand
npm install
```

## Development

```bash
npm run dev
```

Build:

```bash
npm run build
```

Preview with Wrangler:

```bash
npm run preview
```

## Database

Local D1 scripts are included:

```bash
npm run db:migrate:local
npm run db:seed:local
npm run db:console:local
```

Review the Wrangler configuration before running production database commands.

## Deployment

```bash
npm run deploy
```

Configure Cloudflare credentials and project settings first.

## Security

Never commit Cloudflare tokens, database credentials, or other secrets.
