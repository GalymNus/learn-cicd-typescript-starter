# learn-cicd-typescript-starter (Notely) ![tests status](https://github.com/GalymNus/learn-cicd-typescript-starter/actions/workflows/ci.yml/badge.svg)

This repo contains the typescript starter code for the "Notely" application for the "Learn CICD" course on [Boot.dev](https://boot.dev).

## What have I done in this project:

1. Set up a continuous integration pipeline with GitHub Actions that ensures new PRs pass certain checks before they are merged to main:
   a. Unit tests
   b. Formatting checks
   c. Linting checks
   d. Security checks
2. Configured a cloud-based SQLite database hosted on Turso
3. Set up a continuous deployment pipeline with GitHub Actions that does the following whenever changes are merged into main:
   a. Builds a new server
   b. Builds a new Docker image for the server
   c. Pushes the Docker image to the Google Artifact Registry
   d. Deploys a new Cloud Run revision with the new image and serves the app to the public internet

Galym's version of Boot.dev's Notely app.
