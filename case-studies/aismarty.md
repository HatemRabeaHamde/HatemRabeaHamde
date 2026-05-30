# aiSmarty

**AI · SaaS · Shopify Content Optimization**

aiSmarty is an AI-powered Shopify content optimization platform built to help merchants improve product titles, descriptions, and SEO content with AI workflows and one-click publishing back to Shopify.

## Snapshot

| Area | Details |
|---|---|
| Product Type | SaaS platform for Shopify merchants |
| Role | Senior Full-Stack Developer, frontend owner |
| Focus | Shopify OAuth, product sync, AI content workflow, background polling |
| Stack | React 19, Vite, Redux Toolkit, RTK Query, Tailwind CSS, TipTap, JWT |

## Problem

Shopify merchants need a faster way to generate, review, audit, and publish optimized product content without jumping between multiple tools or manually copying AI-generated text.

## Solution

Built a multi-tenant React SPA that connects Shopify stores, syncs products, runs AI generation workflows, audits generated output, and publishes approved content back to Shopify.

## Key Features

- Shopify OAuth store connection
- Product catalog sync
- AI-generated titles, descriptions, and SEO content
- Cross-LLM quality audit workflow
- Background task polling for long-running AI jobs
- One-click publish back to Shopify
- JWT refresh flow and protected app areas

## Architecture Notes

- RTK Query for API state, caching, invalidation, and optimistic UI updates
- Feature-focused frontend structure to separate API calls, UI components, and workflow logic
- Background polling model for AI tasks instead of blocking the UI during long-running operations

## What I Learned

Long-running AI workflows need predictable job state, clear UI feedback, retry-safe polling, and a clean separation between request creation and result delivery.

## Privacy Note

This case study avoids private business logic, credentials, internal URLs, and client-sensitive implementation details.
