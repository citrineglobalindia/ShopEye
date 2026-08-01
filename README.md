# ShopEye — Planning & Status Board

Interactive planning and build-tracking portal for **ShopEye**, a multi-vendor e-commerce marketplace by **Citrine Global India**.

**Live site:** https://shopeye.in _(after DNS is connected)_ · Vercel URL below.

## What this is

A single, self-contained `index.html` (no build step, no dependencies) that tracks the entire ShopEye build:

- **7 domains · 47 modules · 182 sections**
- Every module has a description, functional requirements, a UI/UX plan and a build status
- Filter by role, search, **Board** and **Roadmap** views
- Click any module for its detail; click a status pill to update progress (**To build → Partial → Built**)
- **Export / Import** progress as JSON

The seven domains: Customer Storefront, Seller Center, Admin & Operations, Payments & Finance, Logistics & Fulfilment, Marketing & Growth, and Platform Core & Infrastructure.

## Deploy

This is a static site. On Vercel it needs **no configuration** — framework preset **Other**, output = repository root. Any push to `main` redeploys automatically once the repo is imported.

## Files

| File | Purpose |
|---|---|
| `index.html` | The full portal (self-contained) |
| `logo.png` | ShopEye brand mark |
| `vercel.json` | Static hosting config |

---
© Citrine Global India · ShopEye
