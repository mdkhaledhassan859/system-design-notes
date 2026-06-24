# URL Shortener System

## Requirements
- Shorten long URLs
- Redirect fast

## Design
- API: POST /shorten, GET /{id}
- DB: key-value store

## Scaling
- Use hash or base62 encoding
- Cache hot URLs
