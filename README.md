# Express Middleware Pipeline — Observability Shield

Implemented the Express observability middleware pipeline with request IDs, response logging, request timing, and per-route write auditing.

## Quick Start

```bash
npm install
npm start
```

The API exposes `/posts` and `/users` on port 3000. Every request receives an `X-Request-Id` header and global logger/timing output. The audit logger runs only for `POST /posts`.
