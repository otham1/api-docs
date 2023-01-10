---
sidebar_position: 1
---

# Introduction to the API
Let's discover Out of Character Radio's API.

## Getting Started
Getting started is simple, we don't require any API keys or any authentication when utilizing our API.

### Endpoint URL
The Out of Character Radio API's endpoint URI that we utilize is:
```
https://oocradio.com/api/1.1/wf/
```

### HTTP response codes
- **200 — Success** The request was successfully processed.
- **404 — Endpoint does not exist** This API endpoint does not exist.
- **405 - Wrong Method Used** If you select wrong HTTP method (GET instead of POST for example)