# Cursor Meetup Workspace

An empty workspace prepared for the Cursor meetup. Add demos, exercises, and notes here as the event takes shape.

## Structure

| Folder      | Purpose                          |
|-------------|----------------------------------|
| `demos/`    | Live demo code and walkthroughs   |
| `exercises/`| Hands-on exercises for attendees |
| `notes/`    | Agenda, talking points, links    |

## Getting started

Open this folder in Cursor and use Cloud Agents or local development as needed for meetup prep.

## Deploy to Vercel

This repo ships a minimal static landing page (`index.html`) and is ready for Vercel.

### Option A — Git integration (recommended)

1. In [Vercel](https://vercel.com/new), import `B-Rob97/cursor-meetup-workspace`.
2. Confirm the Vercel GitHub App is installed for your account.
3. Deploy. Future pushes to `main` on GitHub trigger production deploys automatically.

### Option B — CLI from Cloud Agents

1. Create a token at [vercel.com/account/settings/tokens](https://vercel.com/account/settings/tokens).
2. Add it as a Cloud Agent secret named `VERCEL_TOKEN`.
3. From this repo:

```bash
npm install
VERCEL_TOKEN=your_token npm run deploy
```

Preview deploys (non-production): `VERCEL_TOKEN=your_token npm run deploy:preview`
