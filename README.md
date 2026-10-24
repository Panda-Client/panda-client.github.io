# panda-client.github.io

Info website of Panda Client, live at <https://panda-client.github.io>.

Mojang's AppID review links to this site, so it has to describe what the launcher really does. When the launcher's
login, token storage or network connections change, update `index.html` and `privacy.html` in the same go.
The facts come from `docs/MICROSOFT-LOGIN.md` and `docs/ARCHITECTURE.md` in Panda-Client/panda-client.

- Plain HTML + CSS, no build step, no external fonts, scripts or trackers.
- Pushing to `main` publishes the site (GitHub Pages).
- Pages: `index.html`, `privacy.html`, `404.html`. Styles: `style.css`. Images: `assets/`.
- Required on every page: the footer line "NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH
  MOJANG OR MICROSOFT." (Minecraft usage guidelines).
