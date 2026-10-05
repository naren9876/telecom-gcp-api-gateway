# Telecom API Gateway

API Gateway microservice for the Telecom platform.

## Architecture

- **Language:** Go 1.21
- **Framework:** Standard library (net/http)
- **Deployment:** Cloud Run
- **Container Registry:** Artifact Registry

## Endpoints

- `GET /health` - Health check
- `GET /api/v1/gateway` - Gateway status

## Development

Build locally:
```bash
go build -o api-gateway ./cmd/api
```

Run locally:
```bash
./api-gateway
```

Service runs on port 8080.

## Deployment

Automatic deployment on push to main branch via GitHub Actions CI/CD.

## CI/CD Pipeline

- Build Docker image
- Push to Artifact Registry
- Deploy to Cloud Run
# Updated Mon Oct  5 10:00:18 EDT 2026
test
