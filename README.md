# Lois Emma Ewuraesi Taylor: Personal Website

The online home of an author, spoken word artist, and founder of GhanaReads. **One page, one file (`index.html`), no build tools** — editing it is just opening a file and typing.

## How to edit

1. Open `index.html` in any editor (VS Code, Notepad, or GitHub's web editor).
2. Search for ` EDIT` — every spot worth personalizing is marked:
   - Your **headline** and intro (hero)
   - Your **About** story
   - The **one-line pitches** on the Vera and The New Girl cards (still placeholders!)
   - The **GhanaReads** blurb — tell its story in your own words
3. Save, refresh your browser. Done.

### Changing your photo
Replace `profile.jpg` in this folder with any square-ish photo (keep the same filename and nothing else needs to change).

### Changing the look
All colors live in one `THEME` block at the top of the CSS. The palette (`--rose`, `--teal`, `--gold`) is borrowed from the flowers in the photo — change those three to re-theme the whole site. Light and dark mode each have their own block.

### Adding a new story
Copy any `<a class="card">…</a>` block in the Writing section, paste it below, and change the link, title, and blurb. The pink/teal/gold labels rotate automatically.

##  How to publish on GitHub (free hosting)

The magic repo name: **`YOUR-USERNAME.github.io`** — GitHub automatically serves it at `https://YOUR-USERNAME.github.io`.

1. Create a GitHub account if you don't have one, then create a new **public** repo named exactly `YOUR-USERNAME.github.io`.
2. Upload `index.html`, `profile.jpg`, and this `README.md` (drag-and-drop on the repo page works), or from this folder:
   ```
   git init
   git add .
   git commit -m "My personal website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   git push -u origin main
   ```
3. Wait ~1 minute, then visit `https://YOUR-USERNAME.github.io` 

Every future edit: change the file, commit, push — the live site updates automatically. Then add the link to your Linktree, Substack, and Instagram bio.

## Previewing locally

Double-click `index.html` — it opens in your browser. Or run:

```
python -m http.server 8000
```

then open http://localhost:8000.
