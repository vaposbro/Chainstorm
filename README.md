# ChainStorm Capital – Upload-Ordner

So lädst du die Demo auf GitHub Pages:

1. Auf github.com ein neues Repository erstellen (z. B. `chainstorm-capital`), **Public**.
2. Im Repo auf **Add file → Upload files**.
3. **Alle Dateien und Ordner aus diesem `chainstorm-upload`-Ordner** hineinziehen (`index.html`, `assets/`, `favicon.svg`, `icons.svg`, `.nojekyll`). Die Dateien müssen im **Root** des Repos landen, nicht in einem Unterordner.
4. Commit „Initial upload".
5. Repo → **Settings → Pages**.
   - Source: **Deploy from a branch**
   - Branch: **main** / **/ (root)** → Save.
6. Nach ~1 Minute: `https://<dein-username>.github.io/<repo-name>/`

Die App ist eine reine Static Site. Lokal testen: einfach `index.html` im Browser öffnen oder `npx serve .`
