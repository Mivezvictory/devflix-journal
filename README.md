# DevFix Journal (Web)

A focused web app that lets developers journal debugging fixes in under a minute—then find them faster than re-debugging.

## Stack
- Frontend: React + Vite (TS), MUI, React Router, React Hook Form + Zod, TanStack Query
- Backend: Azure Functions (.NET 8 isolated)
- Data: Azure PostgreSQL (FTS), Azure Blob Storage
- Hosting/Auth: Azure Static Web Apps (SWA)
- Observability/Secrets: App Insights, Key Vault

## MVP Goals (v0.1)
- Create a fix entry with 5 required fields in ≤60s
- Search & filter to the right entry in ≤5s
- Secret-scan warning + duplicate hint on create

## Architecture (at a glance)
client (SPA) ⇄ SWA API proxy ⇄ Functions (.NET) ⇄ Postgres (FTS) + Blob (screenshots)
