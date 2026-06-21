# Arafat Hossain Fahim — Portfolio Website

Static portfolio website for GitHub Pages. It is based on the professional CV and project summaries for Arafat Hossain Fahim.

## Files

```text
.
├── index.html
├── styles.css
├── script.js
├── assets/
│   └── Arafat_Hossain_Fahim_CV.pdf
└── README.md
```

## Deploy on GitHub Pages

1. Create a new GitHub repository, for example `arafat-portfolio`.
2. Upload all files from this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save. Your site will be available at:

```text
https://YOUR_GITHUB_USERNAME.github.io/REPOSITORY_NAME/
```

## Customize before publishing

- Replace or update `assets/Arafat_Hossain_Fahim_CV.pdf` when your CV changes.
- Update individual project links in `index.html` if you want each card to point to a specific GitHub repository.
- Update phone number, availability, or personal domain if needed.
- If you have a custom domain, add a `CNAME` file with only the domain name.

## Local Preview

Open `index.html` in a browser, or run a local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```
