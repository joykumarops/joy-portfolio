# Joy Kumar — DevOps Portfolio

A static portfolio website built with HTML, CSS, and vanilla JavaScript.

## Run locally

No build tools or package installation are required.

```bash
cd joy-portfolio
python3 -m http.server 8000
```

Open <http://localhost:8000> in your browser.

## Deploy to Cloudflare Pages (free)

1. Push this directory's contents to the root of the GitHub repository `joykumarops/joy-portfolio`.
2. In Cloudflare Dashboard, open **Workers & Pages** → **Create application** → **Pages** → **Connect to Git**.
3. Select the `joy-portfolio` repository and the `main` branch.
4. Set the build configuration:
   - Framework preset: **None**
   - Build command: leave empty (or `exit 0` if the UI requires a command)
   - Build output directory: `.`
5. Save and deploy. Cloudflare will provide a `*.pages.dev` address and deploy future pushes automatically.

This is a static site; there is no Node.js build step.

## Update the live site

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

## Before publishing

Review the contact email, social profile URLs, experience dates, and all achievement figures. Do not add confidential employer information, internal hostnames/IPs, credentials, or private operational data.
