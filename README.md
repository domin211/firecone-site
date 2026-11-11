# Firecone Hosting

Simple static website for [firecone.eu](https://firecone.eu) — free and low-cost Minecraft hosting.

This is a plain HTML and CSS site. There is no framework and no build step.

## Local preview

From this directory:

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Deploy

The site is ready for [Netlify](https://www.netlify.com/). `netlify.toml` sets the publish directory to the repository root. Connect the GitHub repository in the Netlify dashboard and point the custom domain to `firecone.eu` when you are ready.

## Pages

- `/` — homepage
- `/about/` — history, mission, and infrastructure
- `/contact/` — email and Discord (no form backend)
- `/privacy/` — privacy policy
- `/terms/` — terms and conditions
- `/404.html` — not-found page

External services: [panel](https://panel.firecone.eu/), [client](https://client.firecone.eu/), [Discord](https://discord.firecone.eu/), [status](https://status.firecone.eu/).

Older blog posts from the previous site are stored unpublished in [`/archive`](archive/).
