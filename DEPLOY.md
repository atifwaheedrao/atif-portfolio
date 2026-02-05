# Deploy to GitHub Pages (atif-portfolio)

Your live URL will be: **https://YOUR_GITHUB_USERNAME.github.io/atif-portfolio/**

## Steps

### 1. Create a GitHub account
- Go to [github.com](https://github.com) and sign up (or log in).

### 2. Create the repository
- Click the **+** (top right) → **New repository**
- **Repository name:** `atif-portfolio` (exactly this)
- **Public**
- Leave "Add a README" **unchecked**
- Click **Create repository**

### 3. Upload your site
- Open the **atif-portfolio** repo you just created
- Click **"uploading an existing file"** (or **Add file** → **Upload files**)
- Drag and drop **everything inside** the `SnapFolio` folder:
  - `index.html`
  - `portfolio-details.html`, `service-details.html`, `starter-page.html`
  - `assets` (folder)
  - `forms` (folder)
  - `.nojekyll` (file)
- Scroll down, add commit message: `Initial upload`
- Click **Commit changes**

### 4. Turn on GitHub Pages
- In the repo, go to **Settings** → **Pages** (left sidebar)
- Under **Build and deployment**:
  - **Source:** Deploy from a branch
  - **Branch:** `main` (or `master`) → **/ (root)**
- Click **Save**

### 5. Wait and open your site
- After 1–2 minutes, open: **https://YOUR_USERNAME.github.io/atif-portfolio/**
- Replace `YOUR_USERNAME` with your actual GitHub username

---

## Optional: Resume PDF
To make "Download CV" work, add your `Resume.pdf` in the same folder as `index.html` and upload it with the rest of the files (or add it later and commit again).

## Note: Contact form
The contact form uses PHP, which does not run on GitHub Pages. Buttons and layout will work; the form won’t send emails unless you connect it to a service like [Formspree](https://formspree.io/).
