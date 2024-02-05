# Using LlamaGuard in a Cloudflare Worker

This is, like all of us, a work in progress.

## Installation

```bash
npm install
```

## Develop

```bash
npm run dev
```

Usage

```bash
curl -X POST http://localhost:8787/ -d '{"userContent": "I like guns"}'
```

Response:
```json
{"response":" safe"}
```
