# Machine Rental Platform

**Marketplace · Booking System · Role-Based Access**

Machine Rental is a heavy-machine rental marketplace for listing machines, managing rental bookings, and supporting multiple user roles.

## Snapshot

| Area | Details |
|---|---|
| Product Type | Heavy-machine rental marketplace |
| Role | Sole Full-Stack Developer |
| Focus | Booking lifecycle, OTP login, role-based access, admin reporting |
| Stack | Laravel 12, Sanctum, REST API, React 19, Redux Toolkit, Tailwind CSS |

## Problem

The product needed a structured booking experience for renters and companies while giving admins visibility into users, machines, bookings, and platform activity.

## Solution

Delivered a full Laravel backend and React frontend with machine listings, company machine management, booking lifecycle handling, OTP authentication, and role-specific access.

## Key Features

- Public machine listing
- Company machine CRUD
- Booking lifecycle management
- OTP login and email verification
- Role-based access for admin, company, and renter users
- Admin reporting and operational overview

## Architecture Notes

- Laravel API organized around requests, services, repositories, and resources
- React frontend with centralized state and reusable feature components
- Booking statuses modeled explicitly to keep transitions understandable and maintainable

## What I Learned

Complex booking products are easier to maintain when the state machine is modeled clearly, with explicit transitions and role-specific permissions.

## Privacy Note

This case study avoids private business logic, credentials, internal URLs, and client-sensitive implementation details.
