# Landing Page

A simple static HTML landing page.

## Project Structure

- `index.html` — Main entry point displaying "Hello World"
- `.github/workflows/` — Azure Static Web Apps CI/CD pipeline (original deployment target)

## Running in Replit

The app is served via Python's built-in HTTP server on port 5000:

```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment

Configured as a static site deployment with `publicDir: "."`.
