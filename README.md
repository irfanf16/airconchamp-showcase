# AirconChamp — AC Service Booking Platform

**Field service · Laravel 9**

Booking and job management for air-conditioning maintenance, with customer, technician and admin roles sharing one application.

> **Source code is private.** This repository documents the architecture and engineering work.

## My role
Full-stack engineer — role/permission architecture, booking flow and admin reporting.

## Engineering highlights

**Dual-role architecture.** Customer and technician flows share one Laravel 9 application with cleanly separated route groups, dashboards and notification paths, rather than two codebases kept in sync.

**Granular permissions.** `spatie/laravel-permission` drives role- and permission-based access — admin, technician and customer capabilities defined declaratively and enforced at both route and view level.

**Server-side reporting.** Yajra DataTables processes booking and job tables server-side, so admin views stay responsive as job history grows past what client-side pagination can handle.

**Form-heavy UI.** LaravelCollective HTML for consistent, validated booking and job forms, with SweetAlert for confirmation flows on destructive actions.

**API-ready.** Sanctum token auth in place for mobile technician clients.


## Screenshots

<!-- ![Booking Flow](docs/booking-flow.png) -->
<!-- ![Technician Dashboard](docs/technician-dashboard.png) -->

_Screenshots pending — see `docs/README.md`._

## Stack

`Laravel 9` · `PHP` · `MySQL` · `Blade` · `JavaScript` · `Spatie Permission` · `DataTables` · `Sanctum`
