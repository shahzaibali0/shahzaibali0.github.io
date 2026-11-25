# Shahzaib — Unity Game Developer Portfolio

Single-page portfolio site. Plain HTML, CSS, and JavaScript: no framework, no build step, no backend.

## Structure

```
index.html              All page content and sections
assets/css/style.css    Layout, colours, animations
assets/js/main.js       Scroll progress, reveal-on-scroll, mobile menu, contact form
assets/fonts/           Bowlby One + Sora
assets/images/          Favicon, game covers, app icons
assets/videos/          Hero gameplay video
assets/documents/       CV PDF goes here (Shahzaib_Resume.pdf)
```

## Run locally

```
python -m http.server 5500
```

Then open http://127.0.0.1:5500

## Publish on GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository: Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
3. For the address `https://<username>.github.io/`, name the repository `<username>.github.io`.

## To do

- Add the CV as `assets/documents/Shahzaib_Resume.pdf`.
- Replace the hero gameplay video (`assets/videos/`) and poster with your own game.
