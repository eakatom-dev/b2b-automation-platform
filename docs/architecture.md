# Architecture

## Stage 0 — Static Landing Page

Current architecture:

```text
User
  ↓
Browser
  ↓
Static Landing Page
  ├── index.html
  └── styles.css
```

## Components

- **Browser** — requests, loads, and renders the web page.
- **index.html** — defines the structure and content of the landing page.
- **styles.css** — defines the presentation and layout of the page.

## Current Scope

This stage contains only a static frontend.

There is currently no backend API, database, authentication, queue, container, or cloud infrastructure.

The architecture will expand as those components are actually introduced in later stages.
