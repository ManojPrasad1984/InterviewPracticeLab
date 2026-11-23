# Manoj's Interview Practice Lab

A responsive, standalone interview practice library for .NET, Azure, AI, architecture, delivery, and leadership interviews. It contains 1,050 questions across 20 tracks, including 100 project-specific questions based on all nine projects in Manoj's resume.

## Features

- Search and filter by role or skill, resume project, question type, difficulty, and practice status.
- Progressive Intermediate, Advanced, and Expert follow-up questions on each prompt.
- Answer outlines connected to the resume projects, with fields for personal notes and verified outcomes.
- Random practice mode and local progress tracking.
- No server, API, framework, package installation, or external runtime dependency. Notes and progress stay in the current browser's local storage.
- Responsive layout for desktop, tablet, and mobile screens.

## Run locally

Open `index.html` in a modern browser. All app code is static and included in the page.

## Deploy to Azure Static Web Apps Free

The repository includes a GitHub Actions workflow that deploys the repository root as static files; no app build is required.

1. Create an Azure Static Web App and select the **Free** plan, GitHub as the source, this repository, and the `main` branch.
2. In the Static Web App resource, copy its deployment token. Add it in GitHub under **Settings → Secrets and variables → Actions** as `AZURE_STATIC_WEB_APPS_API_TOKEN`.
3. Push to `main`. The workflow deploys `index.html` and `staticwebapp.config.json`. Pull requests can create preview deployments after the secret is configured.

The app has no API or database dependency. The Free plan is designed for personal projects and does not include an SLA; review current Azure quotas and plan terms before relying on it for production availability.

## Content and privacy

Interview answers are practice outlines, not claims to use verbatim. Add only project details and outcomes you can personally verify. Progress and notes are stored in browser local storage; the app does not send them to a server.
