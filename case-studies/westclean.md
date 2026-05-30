# WestClean

**Payments · Laundry Marketplace · Localization**

WestClean is a laundry marketplace connecting customers, laundries, and admins with role-specific workflows, wallet-style purchasing, and localized interfaces.

## Snapshot

| Area | Details |
|---|---|
| Product Type | Laundry service marketplace |
| Role | Full-Stack Developer |
| Focus | Role-scoped APIs, OTP auth, Moyasar payments, AR/EN localization |
| Stack | Laravel 10, Sanctum, Moyasar, OTP, Spatie Translatable, Bootstrap, Vite |

## Problem

The platform needed to support separate customer, laundry, and admin experiences while keeping authentication, authorization, payments, and localization consistent.

## Solution

Built role-scoped APIs, OTP authentication, Moyasar callback verification, coin-based purchasing, and Arabic/English content support.

## Key Features

- Customer, laundry, and admin roles
- Role-scoped API endpoints
- OTP authentication
- Moyasar payment callback verification
- Coin-based purchasing flow
- Arabic/English localization using translatable content and language files

## Architecture Notes

- API permissions separated by user type to reduce accidental data exposure
- Payment callbacks verified server-side before updating balances or orders
- Localization handled through translatable fields and language resources

## What I Learned

Role-scoped APIs and secure payment callbacks are essential in marketplace products where each actor has different permissions and financial actions.

## Privacy Note

This case study avoids private business logic, credentials, internal URLs, and client-sensitive implementation details.
