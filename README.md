# Deus Ex Lumen — Frontend (GitHub Pages)

Dies ist das Frontend, das bei GitHub Pages gehostet wird.

- Die Playlist-Galerie lädt Videos über den Proxy:  
  `https://deus-ex-lumen-proxy.onrender.com/api/youtube?playlist=...`

- Wenn Proxy/API ausfällt, erscheinen statische Fallback-Embeds.

## Deployment
1. Repo nach GitHub pushen
2. In Settings → Pages → Branch `main` / root auswählen
3. Fertig: Seite läuft unter `https://<username>.github.io/deus-ex-lumen-site/`
