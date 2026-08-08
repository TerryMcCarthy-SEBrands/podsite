# Podsite Constitution

## Core Principles

### I. Static First
All production pages and assets are generated at build time. The app must run as a static site on a static web host without requiring server-side rendering or runtime server logic.

### II. Minimal Runtime
Use only the client-side JavaScript needed for progressive enhancement. Core content and navigation must work without client-side scripting.

### III. Performance and Accessibility
Prioritize fast load times and accessible markup. Use semantic HTML, responsive design, optimized assets, and avoid unnecessary render-blocking resources.

### IV. Content Portability
Source content should be stored in plain text or markdown and transformed into HTML/CSS/JS during the build. Content must be version-controlled and portable.

### V. Simple Deployment
Deployments target static hosting platforms such as GitHub Pages, Netlify, Vercel, or equivalent. Builds must be repeatable, deterministic, and deliver static output only.

## Deployment and Hosting Constraints
The app must use only static assets and build-time tooling in production. No runtime database connections, serverless functions, or dynamic backend code are allowed for published content.
External dependencies must be selected for compatibility with static hosting and kept minimal in size.

## Development Workflow
Validate changes locally before submission. Each pull request must include a successful static build and a review of generated output.
Reviews should confirm that the site remains deployable as a static web app, that no server-side logic has been introduced, and that core pages work without client-side JavaScript.

## Governance
This constitution supersedes other project practices for static web app decisions. Amendments require updating this file and documenting the reason for the change.

**Version**: 1.0.0 | **Ratified**: 2026-08-08 | **Last Amended**: 2026-08-08
