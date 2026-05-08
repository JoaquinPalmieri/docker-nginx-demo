# Nginx Docker Demo

A containerized Nginx web server built as part of my cloud-native learning path.

## Run locally

```bash
docker build -t nginx-demo .
docker run -p 8080:80 nginx-demo
```

Then open http://localhost:8080 in your browser.

## Stack
- Docker
- Nginx (Alpine)