# Irregular Verb Drill

A single-page web app for drilling English irregular verbs: base form → past simple → past participle.

**[Try it live](#)** *(replace with your GitHub Pages link once published — see below)*

## Features

- 148 irregular verbs, with an **easy** mode (120 common verbs) and a **hard** mode (all 148)
- Test past simple only, past participle only, or both at once
- Filter by starting letter (e.g. only verbs starting with B, or B + C)
- Score, streak, and a running list of verbs you've missed
- Score is saved in your browser between visits (no account, no server)
- Works fully offline — it's a single HTML file with no dependencies beyond a Google Font

## Running it locally

No build step required. Just open `index.html` in any browser.

## Publishing with GitHub Pages

1. Create a new repository on GitHub (e.g. `irregular-verb-drill`).
2. Add this project's files to it — at minimum `index.html`.
3. Push to GitHub:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Add irregular verb drill"
   git branch -M main
   git remote add origin https://github.com/Tob1a/irregular-verb-drill.git
   git push -u origin main
   ```
4. On GitHub, go to **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
6. Save. GitHub will publish the site at:
   ```
   https://Tob1a.github.io/irregular-verb-drill/
   ```
   It usually takes a minute or two to go live.

## License

Free to use and modify for personal study.
