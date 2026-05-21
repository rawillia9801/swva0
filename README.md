# Southwest Virginia Chihuahua Admin Dashboard

A polished administrative dashboard for managing every operational area of a Chihuahua breeding business, including puppy and litter tracking, buyer applications, payments, health reminders, transport scheduling, website and buyer portal activity, and integration-ready panels for Twilio and Zoho One.

## What is included

- Premium React and Vite dashboard UI
- Twilio communications command center mock integration
- Zoho One integration health panel
- Puppy, litter, sire, dam, buyer, payments, health, transport, task, and portal modules
- Detailed sample data for realistic business workflow design
- Responsive layout with desktop-first dashboard behavior
- Environment variable template for future live API wiring

## Quick start

```bash
npm install
npm run dev
```

Then open the local URL printed by Vite.

## Build

```bash
npm run build
npm run preview
```

## Integration notes

This front end is intentionally integration-ready but does not expose API secrets in the browser. For production Twilio and Zoho One access, add a secure server or API layer to handle tokens, webhooks, and privileged API calls.

Suggested backend endpoints:

- `POST /api/twilio/send-sms`
- `POST /api/twilio/webhook/inbound-message`
- `POST /api/twilio/webhook/voice`
- `GET /api/zoho/sync-status`
- `POST /api/zoho/sync-buyers`
- `POST /api/zoho/create-invoice`
- `POST /api/zoho/upload-document`

## Dashboard modules

- Executive KPI summary
- Twilio Communications Center
- Zoho One Integration Hub
- Puppy and Litter Overview
- Sires, Dams and Breeding Program
- Buyer Journey Pipeline
- Payments and Financial Overview
- Transport and Delivery Schedule
- Health and Care Overview
- Website and Buyer Portal Activity
- Alerts and Task Queue
