# John H. Solomon, MD — Personal CV Site Setup

This is a customized [al-folio](https://github.com/alshedivat/al-folio) Jekyll site.

## Before you push to GitHub

### 1. Update your GitHub Pages URL in `_config.yml`
Find this line and replace with your actual GitHub username:
```yaml
url: https://johnhsolomon.github.io  # e.g. https://YOUR-USERNAME.github.io
```

### 2. Add your profile photo
Place your photo at: `assets/img/prof_pic.jpg`
(Any standard JPG/PNG works — it will be displayed on the About page)

### 3. Add your CV PDF (optional)
Place your CV PDF at: `assets/pdf/JohnSolomon_CV.pdf`
This enables the download button on the CV page.

### 4. Add social links (optional)
In `_config.yml`, fill in any of these you have:
- `linkedin_username`
- `github_username`
- `orcid_id`
- `research_gate_profile`
- `scholar_userid` (your Google Scholar profile ID)

## Deploying to GitHub Pages

1. Create a new **public** repository on GitHub named `YOUR-USERNAME.github.io`
2. Push this entire folder to that repository
3. Go to **Settings → Pages** → set source to **GitHub Actions**
4. GitHub will automatically build and deploy using the included workflow

The site will be live at `https://YOUR-USERNAME.github.io`

## Local preview (optional)

Requires Ruby + Jekyll:
```bash
bundle install
bundle exec jekyll serve
```
Then visit `http://localhost:4000`
