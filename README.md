# Protocol Party

A playful guide to 19 network services, with illustrated characters and a reverse quiz. Pick all three ridiculous wrong answers while leaving the real answer untouched.

## Run locally

Open `index.html` in a browser. No installation or build required. Fonts load from Google Fonts when online; fallback fonts work offline.

## Publish with GitHub Pages

1. Create a GitHub repository named `protocol-party`.
2. Extract this ZIP, then use **Add file > Upload files** to upload its contents (not the ZIP). Keep `index.html` at the repository root.
3. Commit the files to the `main` branch.
4. Open **Settings > Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, then **main** and **/ (root)**. Save.
6. When deployment finishes, GitHub displays your website URL on the Pages settings screen.

## Edit

All HTML, styles, service descriptions and game logic are in `index.html`. The `data` array contains the real explanations. The `silly` object contains the invented acronym answers.

Common ports are defaults, not guarantees. No accounts, analytics or backend are required. Game scores reset on refresh.
