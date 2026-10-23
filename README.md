# Zero Dollar Store

A Brisbane-supported Australian marketplace for free ($0) items and local pickup, operated by Ground Support Crew.

## Website files

| File | What it does |
| --- | --- |
| [index.html](index.html) | Main homepage, hero and navigation |
| [browse.html](browse.html) | Real listings, categories, search and sorting |
| [wanted.html](wanted.html) | “I Need This” wanted requests |
| [how-it-works.html](how-it-works.html) | How listing, messaging and collection work |
| [safety.html](safety.html) | Safety rules |
| [points.html](points.html) | Zero Dollar Points explanation |
| [about.html](about.html) | About the store, funding and advertising |
| [newsletter.html](newsletter.html) | Newsletter signup |
| [admin.html](admin.html) | Admin landing page; admin controls also appear from the header |
| [assets/styles.css](assets/styles.css) | Shared website CSS (colours, layout, fonts, responsive design) |
| [assets/app.js](assets/app.js) | Shared browser JavaScript (Supabase, listings, account, messaging, reviews) |
| [.nojekyll](.nojekyll) | GitHub Pages static-site setting |

## How to edit

1. Select the file to edit in the GitHub repository's **Code** tab.
2. Click the pencil (**Edit this file**) in the upper-right of the file viewer.
3. Make your edits and commit to `main`.
4. GitHub Pages deploys the changes automatically.

Edit an HTML file to change that page's words/content. Edit `assets/styles.css` for site-wide styling; edit `assets/app.js` for shared behaviour. Keep the code out of `index.html` unless it belongs to the homepage.

**Repository:** https://github.com/125568-star/zerodollarstore

**GitHub Pages project address:** https://125568-star.github.io/zerodollarstore/

**Custom domain (recorded in `CNAME`):** https://zerodollarstore.com

## Backend

The site uses the existing Supabase project for its data, authentication, storage and moderation functions. The browser-side publishable key is intended to be public, but **never** put a Supabase service-role key or any other secret in these files.

The original all-in-one implementation is preserved in the Git history before the modularisation, in case a previous version needs to be reviewed or restored.
