# API Documentation

This repository hosts the OpenAPI specification and interactive documentation for our API.

## Documentation Links

- [Swagger UI Documentation](https://renatodiascosta.github.io/your-api-docs/) - Interactive documentation with Swagger UI

## Development

### Updating the API Specification

To update the API documentation:

1. Export the latest OpenAPI specification from your FastAPI application:
   ```bash
   curl http://localhost:8000/openapi.json > openapi.json
   ```

2. Commit and push the updated specification:
   ```bash
   git add openapi.json
   git commit -m "Update API specification"
   git push
   ```

### Local Testing

To test the documentation locally, you can use a simple HTTP server:

```bash
# Python 3
python -m http.server
```

Then visit `http://localhost:8000` in your browser.