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

Start the local frontend:

```bash
npm run dev
```

Build:

```bash
npm run build
```

Run the built site locally with Cloudflare Pages:

```bash
npm run preview
```

## Local Database

The project includes Cloudflare D1 scripts for creating, migrating, seeding, and inspecting the local database.

```bash
npm run db:migrate:local
npm run db:seed:local
npm run db:console:local
```

## Production Database

Production D1 operations are available through the corresponding `db:migrate:prod`, `db:seed:prod`, and `db:console:prod` scripts. Review the Wrangler configuration before running production commands.

## Deployment

```bash
npm run deploy
```

Configure your Cloudflare project and credentials before deployment.

## Security

Never commit Cloudflare API tokens, database credentials, or other secrets.
