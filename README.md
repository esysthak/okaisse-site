# Okaisse website

Showcase website for Okaisse, the till for used-phone shops in Morocco. One static page, French by default, with Arabic (right to left) and English.

- `index.html`: the whole page (text in the three languages is in the script at the bottom).
- `images/app-screen.jpg`: screenshot of the app.
- `site.json`: number, prices, picture and all texts (FR / AR / EN), edited from Pages CMS (`.pages.yml`); the page loads it on start.

To change the WhatsApp number, edit the line `const WHATSAPP = "212600000000";` in `index.html` (international format, digits only).

Hosted for free with GitHub Pages (Settings > Pages > Deploy from a branch > `main` / root).
