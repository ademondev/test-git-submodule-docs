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

### POST /api/users
Creates a new user.

**Request Body:**
```json
{
  "name": "string",
  "email": "string"
}
```

**Response:**
```json
{
  "id": 3,
  "name": "New User",
  "email": "newuser@example.com",
  "created": "2026-04-17T10:00:00Z"
}
```

### DELETE /api/users/:id
Deletes a user by ID.

**Response:**
```json
{
  "message": "User deleted successfully"
}
```