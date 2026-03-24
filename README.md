# The Teutonic Knights — Deutscher Orden

A cinematic, single-page website documenting the 835-year history of the Teutonic Knights, from the Siege of Acre in 1191 to their survival as a charitable order today.

## Live Site

Deploy this repo to [Netlify](https://netlify.com), [Vercel](https://vercel.com), or [GitHub Pages](https://pages.github.com) for free static hosting.

## Structure

```
index.html          # Main page (references external CSS/JS)
css/
  tailwind.css      # Compiled Tailwind CSS framework
  custom.css        # Custom animations, dossier cards, timeline
js/
  main.js           # Scroll animations, navbar, mobile menu
```

## Features

- **Cinematic design** — Dark theme with gold (#C9A84C) and blood red (#8B0000) accents
- **Responsive** — Works on desktop, tablet, and mobile
- **Scroll animations** — Intersection Observer-powered reveal effects
- **Custom typography** — Cinzel, Crimson Text, Inter, JetBrains Mono via Google Fonts
- **Historical images** — Served from Wikimedia Commons (public domain)
- **Dossier aesthetic** — Declassified file labels, archive traces, redacted zones

## Sections

1. Hero with animated Teutonic cross shield
2. Origins — The Siege of Acre, 1191
3. Hospital to Holy Army
4. Empire of Sword & Cross
5. Malbork Castle
6. The Black Cross — Visual Technology
7. Battle of Grunwald, 1410
8. Survival to Present Day
9. 835-Year Timeline
10. Redacted Files — Documented Layered Continuity

## Deploy

### Netlify (easiest)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Connect this GitHub repo
3. Deploy — no build step needed

### GitHub Pages
1. Go to repo Settings → Pages
2. Set source to `main` branch, root folder
3. Save — site will be live at `https://vltramk.github.io/teutonic-knights/`
