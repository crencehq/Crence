# Crence portfolio — Vercel-ready starter

A responsive, static HTML/CSS/JS portfolio for Crence. No build step or framework is required; Vercel can host this as a static site.

## Before publishing

1. Open `index.html`.
2. Find `YOUR_EMAIL@example.com` and replace it with the email address you want clients to use.
3. Replace the sample project visuals with your real Tranxact work and your actual advertising/film projects as you create them. The non-Tranxact projects are explicitly labelled as concepts.
4. Preview locally by opening `index.html` in a browser.

## Deploy to Vercel (easy route using GitHub)

1. Sign in to GitHub and create a new repository named `crence-portfolio` (public or private is fine).
2. Upload `index.html` and this `README.md` to the repository root.
3. Sign in to Vercel at https://vercel.com and choose **Add New → Project**.
4. Import the `crence-portfolio` GitHub repository.
5. For a plain static HTML site, leave the framework preset as **Other** and leave Build Command and Output Directory empty. The site entry file is at the repository root.
6. Select **Deploy**. Vercel will provide a live `*.vercel.app` URL.
7. Whenever you update the files in GitHub, Vercel will redeploy automatically.

## Optional: custom domain

After the first deployment, open the project in Vercel → Settings → Domains and add a domain you own. Follow Vercel's DNS instructions exactly.

## Notes

- This starter uses Google Fonts, so the font choices require an internet connection; fallback fonts are defined.
- The contact button is a `mailto:` link and does not submit to a server. Replace the placeholder email before publishing.
- No analytics, tracking scripts, database, or server-side features are included.
