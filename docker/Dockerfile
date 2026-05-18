## 🐳 Docker

### `docker/Dockerfile`
```dockerfile
FROM httpd:2.4-alpine

# Copy custom website content
COPY html/ /usr/local/apache2/htdocs/

# Expose port 80
EXPOSE 80

# Health check
HEALTHCHECK --interval=30s --timeout=3s --start-period=5s --retries=3 \
  CMD wget --no-verbose --tries=1 --spider http://localhost/ || exit 1
