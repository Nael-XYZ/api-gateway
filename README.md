# API Gateway 🚪

Production API gateway with rate limiting, auth, and load balancing.

## Features

- **Rate Limiting**: Per-user, per-IP, per-API-key
- **Authentication**: JWT, API key, OAuth2
- **Load Balancing**: Round-robin, least-conn, IP-hash
- **Request Transformation**: Header injection, path rewrite
- **Circuit Breaking**: Auto-failover on backend errors

## Deploy

```bash
nginx -c gateway/nginx.conf
```

## License

MIT