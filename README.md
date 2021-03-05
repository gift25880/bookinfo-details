# Bookinfo Detail Service

## How to run with Docker

```bash
# Build Docker Image for detail service
docker build -t details .

# Run details service on port 8080
docker run -d --name details -p 8080:8080 details
```

* Test with path `/details/***` and `/health`