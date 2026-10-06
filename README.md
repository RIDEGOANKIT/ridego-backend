# RideGo Real Backend Starter

This is the first real backend layer for RideGo: Express API + PostgreSQL + JWT auth + customer rides + driver status + admin stats.

## Run locally
1. Install Docker Desktop.
2. From this folder run: `docker compose up`
3. API health: `http://localhost:8080/health`

## Production
Deploy PostgreSQL and Node API on your chosen host, set DATABASE_URL/JWT_SECRET/CORS_ORIGIN, then connect the Android/web client to the HTTPS API URL.

## Still required before public launch
SMS OTP provider, Google Maps/Routes key, real-time WebSocket/location service, payment gateway, push notifications, driver KYC/document verification, production secrets, monitoring, backups, privacy/terms, and applicable Indian transport/aggregator compliance.
