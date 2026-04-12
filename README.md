# oeyo.net

Personal site — travel guides, projects, and a bit about me.

Live at [www.oeyo.net](https://www.oeyo.net)

## Structure

```
index.html          Homepage
about.html          About page
travel/
  index.html        Travel hub
  pacifica.html     Pacifica guide
  san-francisco.html  San Francisco guide
  norway.html       Norway guide
css/
  style.css         All styles
```

## Development

Static HTML/CSS — no build step.

```bash
npx serve .
```

Then open `http://localhost:3000`.

## Deployment

Deployed via [Netlify](https://netlify.com) on every push to `main`. Custom domain configured in Netlify's domain settings.
