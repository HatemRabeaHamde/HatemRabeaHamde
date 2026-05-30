# Saedni

**Payments · Automotive Platform · Subscriptions**

Saedni is a bilingual automotive services platform covering vehicle subscriptions, inspections, towing, replacement car rentals, and payment flows.

## Snapshot

| Area | Details |
|---|---|
| Product Type | Automotive services and subscription platform |
| Role | Full-Stack Developer |
| Focus | Payments, subscriptions, Firebase notifications, RTL/LTR support |
| Stack | Laravel 12, PHP 8.3, Sanctum, MyFatoorah, Firebase, Spatie, Pest |

## Problem

The platform needed to handle service subscriptions and payments reliably while supporting Arabic/English users, admin operations, and different automotive service flows.

## Solution

Built secure backend workflows for subscriptions, payment verification, service fulfillment, notifications, and dashboard operations with localization-ready UI support.

## Key Features

- Vehicle subscription management
- Inspection, towing, and replacement rental workflows
- MyFatoorah payment integration
- Firebase push notifications
- Arabic/English RTL/LTR support
- Admin dashboard for service and subscription management
- Scheduled jobs for subscription state transitions

## Architecture Notes

- Layered Laravel structure using validation, services, and API resources
- Payment lifecycle designed around pending payment creation, webhook verification, and fulfillment
- Idempotency and row-level locking for safer payment handling

## What I Learned

Reliable subscription billing depends on webhook verification, duplicate protection, clear payment states, and safe fulfillment after confirmed provider responses.

## Privacy Note

This case study avoids private business logic, credentials, internal URLs, and client-sensitive implementation details.
