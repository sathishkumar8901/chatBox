### Base URL : http://localhost:3000

### API Endpoint: `POST /api/user/registerUser`

#### Request Parameters:
```json
{
  "name": "daniel",
  "password": "Password@#123"
}

### Response:
{
  "message": "User registered successfully"
}

### API Endpoint: `POST /api/user/login`
```json
{
  "name": "daniel",
  "password": "Password@#123"
}

### Response : 
{
    "messge": "Login Successfully",
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6MTEsInVzZXJuYW1lIjoiZGFuaWVsIiwiaWF0IjoxNzMzOTIyMTYwLCJleHAiOjE3MzM5MjU3NjB9.4cyv7Omr-TjXped831YY71lvDBnx357qmhXU5fuSgac"
}

### API Endpoint: `GET /api/user/csvExport`
#### Authorization:
- **Bearer Token**: {$token}
#### Response:
```json
{
  "message": "Chat exported successfully"
}


