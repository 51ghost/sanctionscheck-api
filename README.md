# SanctionsCheck API

OFAC, EU, and UN sanctions lists screening for entities and individuals

## Quick Deploy
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new)

## Authentication
All endpoints require `x-api-key` header (except `/v1/health`).

## Endpoints
- `GET /v1/health` - Health check

## RapidAPI Pricing
| Plan | Price | Requests/Day |
|------|-------|-------------|
| Free | $0 | 100 |
| Basic | $9.99/mo | 5,000 |
| Pro | $49.99/mo | 50,000 |
| Enterprise | $499.99/mo | Unlimited |

## Deploy to Railway
1. Click "Deploy on Railway" button
2. Set `INTERNAL_API_KEY` env var
3. Add to RapidAPI dashboard pointing to your Railway URL
