# Обои для iPhone — project website

Public informational website for the independent wallpaper project and its internal **Oboi Wallpaper Publisher** integration.

## Files

- `index.html`: project information, official community links, application description and English overview.
- `privacy.html`: privacy policy with a Russian summary.
- `styles.css`, `assets/`: local styles and original SVG illustrations. No build, JavaScript, external fonts, analytics, or dependencies.

## Preview

Run `python -m http.server 8769 --bind 127.0.0.1` from this directory, then open `http://127.0.0.1:8769/`.

## Publish on GitHub Pages

Create a dedicated public repository containing only these website files. In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**. Wait for the Pages deployment and verify the actual homepage and `privacy.html` URLs before entering them in the Pinterest application.

Do not upload bot source code, configuration, credentials, logs, or account tokens. This repository does not enable Pinterest publishing or submit an API application.

Operator contact: [VK community messages](https://vk.com/im?sel=-172421211).
