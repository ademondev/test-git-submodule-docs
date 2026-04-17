# API Reference

## Endpoints

### GET /api/health
Returns the health status of the API.

**Response:**
```json
{
  "status": "ok",
  "timestamp": "2026-04-17T10:00:00Z"
}
```

### GET /api/users
Returns a list of users.

**Response:**
```json
{
  "users": [
    {
      "id": 1,
      "name": "John Doe",
      "email": "john@example.com"
    }
  ]
}
```