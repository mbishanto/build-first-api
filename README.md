# Build First API

A simple Express.js API built for the FlyRank Backend AI Engineering Internship assignment.

## Endpoints

### GET /

Returns a welcome message.

Example response:

```json
{
  "message": "Hello FlyRank!"
}
```

### GET /status

Returns the current server status and timestamp.

Example response:

```json
{
  "status": "OK",
  "time": "2026-07-09T15:42:31.123Z"
}
```

## Technologies Used

- Node.js
- Express.js

## Run Locally

```bash
npm install
node index.js
```