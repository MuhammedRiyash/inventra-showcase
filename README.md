# Inventra — Inventory That Compounds

> **Thanks for visiting!** Inventra is a private project, so its source code lives in a private repository.
> If you're reviewing my application and would like to see the code, I'm happy to share it.
>
> **[Request access to the source →](mailto:thisismd.riyash@gmail.com?subject=Inventra%20source%20code%20access%20request&body=Hi%20Muhammed%2C%0A%0AI%27d%20like%20to%20review%20the%20Inventra%20source%20code.%20My%20GitHub%20username%20is%3A%20)**
> — or message me on [LinkedIn](https://www.linkedin.com/in/muhammedriyash). Send your GitHub username and I'll add you as a read-only collaborator.

---

## What it is

Inventra is an inventory management dashboard for small and mid-size retail and wholesale businesses: vendors,
purchase orders, warehouses, just-in-time controls, sales billing and 15+ inventory-effectiveness ratios in one place.
I designed and built it on my own.

| | |
|---|---|
| **Framework** | Next.js 16 (App Router, Turbopack), React, TypeScript |
| **Data** | Prisma, PostgreSQL |
| **Auth** | NextAuth v5 (credentials, JWT) with role-based access |
| **UI** | Tailwind CSS v4, shadcn/ui (Radix), Recharts |
| **Forms** | react-hook-form with Zod validation |
| **Quality** | Vitest unit tests, Playwright end-to-end tests |
| **Hosting** | Vercel |

## Highlights

- **Procure-to-bill flow** — vendors, purchase orders, warehouse stock, just-in-time (JIT) controls and sales billing in a single workflow.
- **Inventory analytics** — 15+ effectiveness ratio cards, charts built with Recharts, and an EOQ (economic order quantity) widget.
- **Four roles** — admin, manager, clerk and accountant, each limited to the screens they need.
- **Tested core maths** — unit tests cover the ratio, EOQ and vendor-ID logic; an end-to-end test walks login → vendor → purchase order → bill.

## Status

Built in May 2026 (15 commits).

---

**Muhammed Riyash J** · Senior Full-Stack Developer · Bengaluru, India

[Portfolio](https://md-riyash-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/muhammedriyash) · [GitHub](https://github.com/MuhammedRiyash)
