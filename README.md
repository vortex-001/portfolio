# Harsh Garg — DevFest Portfolio

A responsive personal developer portfolio created for the GDG Gurugram DevFest volunteer application. Built with plain HTML, CSS, and JavaScript — no build step required.

## Features

- Bold editorial typography with warm ivory, burnt orange, and lilac accents
- Responsive desktop, tablet, and mobile layouts
- Animated ticker, rotating orbit detail, and scroll-reveal transitions
- Mobile navigation
- About, skills, projects (JevQL, ReVeil, StudyBuddy AI), community, and contact sections
- Reduced-motion support and basic accessibility considerations
- No external JavaScript dependencies

## Run locally

1. Extract the ZIP.
2. Open `index.html` in a browser, or use VS Code's Live Server extension.
3. Check the profile links and update any details before publishing.

## Personalize before deploying

Open `index.html` and:
- Your profile photo is stored at `assets/harsh-garg.jpg`; replace it with a new photo at the same path if you want to update it.
- Your contact email is set to `harshji93061@gmail.com`.
- Replace the GitHub profile links in each project card with direct repository URLs when available.
- Review all project descriptions and skill tags to ensure they accurately represent your current work.

The uploaded profile photo is already wired into the hero section at `assets/harsh-garg.jpg`.

## Deploy to Vercel

### Option A — GitHub (recommended)
1. Create a new repository on GitHub, for example `devfest-portfolio`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Sign in at [Vercel](https://vercel.com/) using GitHub.
4. Select **Add New → Project**, then import your `devfest-portfolio` repository.
5. Framework preset: **Other**. Build command: leave blank. Output directory: leave blank or use `.` if required by the dashboard.
6. Click **Deploy**. Vercel will provide a public URL such as `devfest-portfolio-yourname.vercel.app`.
7. Open the URL on your phone and desktop to test it. Submit that live URL in the GDG Gurugram volunteer form.

### Option B — Vercel CLI
Install Node.js first, then run in the project folder:
```bash
npm install -g vercel
vercel
```
Follow the prompts. To publish a production deployment:
```bash
vercel --prod
```

## Suggested form submission

Paste your live Vercel URL into the **Portfolio / GitHub / Behance / Instagram Profile** field. You can also share your GitHub profile directly: https://github.com/vortex-001

## Notes

- The contact email is set to `harshji93061@gmail.com`.
- Project cards currently link to the GitHub profile because individual repository URLs were not supplied.
- Do not claim a project is production-ready unless that matches its current status.


## Project UI preview images

The `assets/jevql-ui.svg`, `assets/reveil-ui.svg`, and `assets/studybuddy-ui.svg` files are crisp, scalable interface mockups used in the project cards. They are illustrative previews, not screenshots from live deployed applications. Replace them with real screenshots when you have them.


## Header and scrolling update
- Added GitHub and LinkedIn icons to the header, linking to the supplied profiles.
- Clipped horizontal overflow to prevent the bottom horizontal scrollbar while keeping vertical scrolling enabled.
