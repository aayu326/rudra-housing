# RUDRAA CRM — Interactive Demo

A browser-based, client-presentation demo for Rudraa Housing India.

## Run
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, Safari or Firefox.
3. Sign in with one of the demo accounts below.

## Demo accounts
All accounts use password: `Rudraa@123`

- Admin: `admin@rudraademo.com`
- Sales Manager: `manager@rudraademo.com`
- Telecaller: `telecaller@rudraademo.com`
- Sales Executive: `sales@rudraademo.com`

This is a front-end demonstration. Role selection changes the displayed identity but does not implement secure authentication or production permissions.

## Included
- Admin-style dashboard and KPI cards
- Lead management with add/edit, search, filters and duplicate-phone check
- Sales pipeline with stage updates
- Simulated call monitoring and sample recording preview
- Follow-up management
- Site visit scheduling
- Employee directory and demo employee creation
- Projects and illustrative inventory
- Booking and sample payment tracking
- Reports and CSV export
- Browser localStorage persistence

## Important limitations
- Calls are simulated. No real calls are placed and no actual conversations are recorded.
- Recording preview is a placeholder, not an audio recording.
- Demo credentials are not secure authentication.
- Data is stored in the current browser using localStorage and is not shared between users or devices.
- No Supabase connection, production database, RLS, telephony provider, payment gateway or server-side authorization is configured.
- Seed names, call activity, prices, inventory and bookings are fictional/illustrative and must be verified before any business use.

## Production next steps
Configure Supabase Auth and PostgreSQL, migrate the schema, implement server-side authorization and RLS, provision secure storage, connect a telephony provider (e.g. Exotel / MyOperator / Knowlarity), configure verified webhooks and consent-aware recording access, then run tests and deploy.
