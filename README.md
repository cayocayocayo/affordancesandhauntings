# affordances and hauntings

Personal blog. Plain static HTML, no build step. Moved from Neocities.

## Layout

- `index.html` : home page (links, noise box, writing list, guestbook)
- `writing/*.html` : one file per post. Add a new post by copying an existing one, then add an `<li>` for it in the writing list in `index.html`.

## Deploying (Cloudflare Pages)

Workers & Pages > Create > Pages > Connect to Git > pick this repo, then:

- Production branch: `main`
- Framework preset: None
- Build command: (leave empty)
- Build output directory: `/`

Every push to `main` then redeploys. Other branches get preview URLs.
