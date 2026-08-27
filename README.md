# Mehak Naseem — Portfolio

A vanilla HTML/CSS/JavaScript portfolio for Data Science, Machine Learning and Data Analytics.

## Files

- `index.html` — portfolio content
- `style.css` — design and responsive layout
- `script.js` — navigation and project filtering

## Before publishing

Update the GitHub links on project cards once each repository URL is confirmed. The current version links most project cards to the GitHub profile rather than inventing repository URLs.

## Run locally

Open `index.html` in a browser, or use the VS Code Live Server extension.

## Azure

This is intentionally a no-framework static site, which fits Azure Static Web Apps. Microsoft documents GitHub integration and automatic deployment for Static Web Apps.

Recommended path:

1. Create a GitHub repository for this portfolio.
2. Push these files to the `main` branch.
3. Create an Azure Static Web App and connect the GitHub repository.
4. Select the no-framework/custom option.
5. Let Azure create the GitHub Actions deployment workflow.
6. Future pushes to `main` can trigger automatic deployments.
