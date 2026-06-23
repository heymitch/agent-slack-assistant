# Agent Slack Assistant

A no-backend, single-file web tool that generates a Slack app manifest and a 512×512 app icon for your Hermes agent. Everything runs in your browser — nothing is uploaded, stored, or logged.

## Use it

Just open `index.html` in your browser. Double-click it, or from a terminal run:

```bash
open index.html
```

No install, no build, no server.

## Steps

1. Enter your name, agent name, and brand (defaults to "Agent"), plus your Slack member ID.
2. Click **Generate manifest**.
3. Go to [api.slack.com/apps](https://api.slack.com/apps) → **Create New App** → **From an app manifest** → paste the manifest → **Create**.
4. Drag your image onto the **App icon** box, download the 512×512 PNG, then upload it in Slack under **Basic Information → Display Information → App icon**.

## Customize the brand

The agent name defaults to `AgentName (YourName's Agent)`. Change the **Brand** field to anything you like (Sidekick, Copilot, etc.) and the name updates live.

## Deploy (optional)

It's a static file, so you can host it free on Vercel, Netlify, or GitHub Pages if you want a shareable link. You don't need to — opening the file works just fine.

## Privacy

No backend, no tracking, nothing leaves your browser.
