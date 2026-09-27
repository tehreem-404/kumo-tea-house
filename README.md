# Kumo Tea House

A Kyoto-inspired tea atelier website — collection, cellar, ceremony booking, and journal — designed to feel quiet, seasonal, and considered.

**Case study:** https://my-portfolio-9az2.vercel.app/projects/kumo-tea-house
**Repository:** https://github.com/tehreem-404/kumo-tea-house

---

## About

Kumo Tea House is a brand/product site built as part of Tehreem Kanwal's web engineering portfolio. It presents a fictional tea house through several sections:

- **Collection** — the tea offerings
- **Cellar** — aged/stored tea inventory
- **Ceremony booking** — reserving a tea ceremony
- **Journal** — editorial/blog-style content

## Tech Stack

Confirmed from the repo's `package.json`:

- **Frontend:** React 19, TanStack Start / Router / Query / Table
- **Styling / UI:** Tailwind CSS v4, Radix UI primitives, shadcn-style components (class-variance-authority, cmdk, sonner, vaul)
- **Forms & validation:** React Hook Form, Zod
- **State:** Zustand
- **Auth:** better-auth, jose (JWT)
- **Database:** PostgreSQL via Kysely (query builder), with `pg` driver and `@electric-sql/pglite` for local/embedded Postgres
- **Build tooling:** Vite 8, TypeScript, ESLint, Prettier
- **Testing/automation:** Playwright
- **Server runtime:** Nitro

## Getting Started

```bash
# Clone the repository
git clone https://github.com/tehreem-404/kumo-tea-house.git
cd kumo-tea-house

# Install dependencies
npm install

# Run the dev server (default port 8080)
npm run dev
```

## Available Scripts

These are the actual scripts defined in `package.json`:

| Command | What it does |
|---|---|
| `npm run dev` | Starts the Vite dev server on `0.0.0.0:8080` |
| `npm run build` | Builds the app and runs database migrations |
| `npm run db:migrate` | Runs database migrations |
| `npm run preview` | Builds/serves a preview |
| `npm run typecheck` | Runs TypeScript type checking (`tsc --noEmit`) |
| `npm run lint` | Runs ESLint |
| `npm run format` | Formats code with Prettier |
| `npm test` | Runs the test suite |

## Contact

- **Email:** tehreemkanwal404@gmail.com
- **LinkedIn:** [linkedin.com/in/tehreem-kanwal-5481362a4](https://www.linkedin.com/in/tehreem-kanwal-5481362a4)
- **GitHub:** [github.com/tehreem-404](https://github.com/tehreem-404)


