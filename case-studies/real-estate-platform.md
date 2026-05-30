# Real Estate Platform

**Multi-vendor · Contracts · PDF Generation · Performance**

This real estate platform included marketplace features, property modules, contracts, seller commerce, invoice generation, and admin operations.

## Snapshot

| Area | Details |
|---|---|
| Product Type | Multi-vendor real estate and commerce platform |
| Role | Full-Stack Developer and Tech Lead |
| Focus | Legacy rescue, contracts, invoices, PDFs, localization, performance |
| Stack | Laravel 10, PHP 8.1, Sanctum, Spatie, DomPDF, Blade, Livewire, MySQL |

## Problem

The project needed stabilization, feature completion, and performance improvements while supporting multiple business domains inside the same platform.

## Solution

Stabilized the legacy codebase, delivered marketplace and real estate modules, added contract and invoice workflows, improved API speed, and supported Arabic/English localization.

## Key Features

- Multi-vendor marketplace
- Land, building, opportunity, and renter contract modules
- Seller commerce workflows
- Invoice and PDF generation
- Admin dashboard
- Arabic/English localization with RTL/LTR support
- API and page-load performance improvements

## Architecture Notes

- Domain workflows separated into clearer service-level responsibilities
- PDF generation handled server-side for invoices and business documents
- Query optimization, eager loading, and caching used to improve slow paths

## What I Learned

Server-side PDF generation and query optimization become critical under load, especially when dashboards and business documents depend on aggregated data.

## Privacy Note

This case study avoids private business logic, credentials, internal URLs, and client-sensitive implementation details.
