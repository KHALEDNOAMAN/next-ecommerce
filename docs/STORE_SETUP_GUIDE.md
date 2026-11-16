# Next Ecommerce - Store Setup Guide

## Overview
Free, modern e-commerce platform built with Next.js 16 and Payload CMS.

## Features
| Feature | Description |
|---------|-------------|
| Dynamic Storefront | Product listings, categories, search |
| Content Management | Payload CMS for products & pages |
| Cart & Checkout | Full shopping flow |
| SEO Optimized | Meta tags, sitemaps, structured data |
| Responsive | Mobile-first design |

## Quick Start
```bash
git clone https://github.com/buildlabs-io/next-ecommerce.git
cd next-ecommerce
cp .env.example .env
npm install
npm run dev
```

## Customization
| What | Where |
|------|-------|
| Products | Payload CMS admin panel |
| Theme | tailwind.config.ts |
| Pages | app/ directory (Next.js) |
| Payments | Stripe integration config |

## Deployment
| Platform | Command |
|----------|---------|
| Vercel | vercel deploy |
| Docker | docker-compose up -d |