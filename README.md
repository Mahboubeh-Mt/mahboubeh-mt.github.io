# Personal Site Starter

A clean, single-page personal website you can deploy to **GitHub Pages** (your-username.github.io) or **GitLab Pages**.

## 1) Edit your info

Open `index.html` and update:

- `YOUR-USERNAME` (GitHub & GitLab links)
- `YOUR-LINKEDIN` (your LinkedIn handle)
- `YOUR-SCHOLAR-ID` (Google Scholar user id)
- Replace `assets/Mahboubeh_Motaghi_CV.pdf` with your actual CV (or remove the button)

## 2) Deploy on GitHub Pages (your-username.github.io)

1. Create a **GitHub** account (if you don’t have one).
2. Create a new repo **named exactly**: `YOUR-USERNAME.github.io`
3. Upload all files from this folder to the repo root:
   - On GitHub, click **Add file → Upload files** → drag/drop → **Commit**.
   - Or use git:
     ```
     git init
     git branch -M main
     git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
     git add .
     git commit -m "Initial site"
     git push -u origin main
     ```
4. Visit `https://YOUR-USERNAME.github.io` (may take ~1–2 minutes to appear).

## 3) Deploy on GitLab Pages (your-username.gitlab.io)

1. In **GitLab**, create a new **Project** called e.g. `personal-site`.
2. Push these files to the repo root.
3. The provided `.gitlab-ci.yml` publishes the site automatically:
   - Your site will be at: `https://YOUR-USERNAME.gitlab.io/personal-site/`
4. To use `YOUR-USERNAME.gitlab.io` root, create a project named **`YOUR-USERNAME.gitlab.io`** and push the site there.

## 4) Optional

- Add a custom domain in GitHub/GitLab Pages settings (add a `CNAME` DNS record).
- Replace icons with local SVGs if you prefer; current ones use SimpleIcons CDN.
- Add real screenshots to `assets/og-image.png` for rich social sharing.

---

**Tip:** Keep it short, visual, and action-oriented. Showcase 2–4 projects with clear links.
