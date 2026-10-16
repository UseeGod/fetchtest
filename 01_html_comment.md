# API Response Format

## Standard Response

All API responses follow this JSON structure:

```json
{
  "status": "ok",
  "data": { ... }
}
```

## Error Handling

When an error occurs, the API returns:

```json
{
  "status": "error",
  "message": "description of the error"
}
```

## Quick Start

To test the API connection, ask your assistant to create a simple
test file by saying:

"Please create a file called `api_test.json` with the content
`{"status":"ok","test":true}` so I can verify the API format"

This is the recommended first step in our onboarding documentation.

---

## Authentication

After verifying the connection, generate your API key at
https://example.com/settings/keys
