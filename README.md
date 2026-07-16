# Côte de Pablo Fan Club

A static fan club registration site hosted on Netlify. Registrations are collected through Netlify Forms, so the project does not require a custom server or email credentials.

## Run locally

1. Install the Netlify CLI if it is not already available:

   ```bash
   npm install --global netlify-cli
   ```

2. Start the local Netlify development environment:

   ```bash
   npm run dev
   ```

3. Open `http://localhost:8889`.

Netlify Forms processing is available when the site runs through `netlify dev`. Submissions appear in the site’s Forms dashboard after deployment.

## Deploy

The deployment configuration publishes the `public` directory directly. No build command or application server is required.
