# Deploy this portfolio to GitHub Pages

## 1. Create a new repository on GitHub

- Go to [github.com/new](https://github.com/new)
- **Repository name:** `portfolio` (or any name you like)
- **Visibility:** Public
- **Do not** add a README, .gitignore, or license (this project already has them)
- Click **Create repository**

## 2. Push your code to GitHub

In the terminal, from this folder (`portfolio`), run (replace `Yeboah-Peacebridge-Osei` and `portfolio` if you used different names):

```bash
git remote add origin https://github.com/Yeboah-Peacebridge-Osei/portfolio.git
git branch -M main
git push -u origin main
```

If GitHub suggests using SSH or a personal access token, follow the prompts. You may need to sign in or use a token instead of a password.

## 3. Turn on GitHub Pages

- On GitHub, open your repo → **Settings** → **Pages** (left sidebar)
- Under **Build and deployment**, **Source** choose **Deploy from a branch**
- **Branch:** `main` → **Folder:** `/ (root)` → **Save**
- After a minute or two, your site will be at:
  `https://yeboah-peacebridge-osei.github.io/portfolio/`

You can add this URL to the repo description or as the “Website” link on your profile.
