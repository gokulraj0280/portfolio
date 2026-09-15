<div align="center">

# 🧭 Gokulraj S — Portfolio

### Full-stack developer &nbsp;·&nbsp; AI-focused CS engineer &nbsp;·&nbsp; Hosur, India

A single-page portfolio styled like an engineering drafting sheet — blueprint
grid lines, spec tables, and drawing-sheet numbering — built to match a
full-stack, systems-minded background.

[![Made with HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](#)
[![Made with CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](#)
[![Made with JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](#)
[![No dependencies](https://img.shields.io/badge/dependencies-none-1E7A6E?style=flat)](#)
[![Deploy with GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-222?style=flat&logo=github)](#-deploying-to-github-pages)

**[🔗 View the live site](https://gokulraj0280.github.io/portfolio/)** &nbsp;·&nbsp; *(link goes live after deployment — see below)*

</div>

<br>

## 📐 What this is

A single `index.html` file — markup, styles, and script all in one place, no
build tools, no dependencies. It's a straight translation of my résumé into a
site:

- **Profile** — who I am and what I build
- **Experience** — internships at Intarm Technologies and Adviyo Technologies
- **Projects** — LockVault, CollabSync Pro, Sparkle Chat AI, Real Estate
  Management Portal, Artistic Hub
- **Stack** — languages, frameworks, databases, and tools as a spec table
- **Coding profile & certifications** — LeetCode stats and certificates
- **Education & achievements**
- **Contact** — email, phone, LinkedIn, GitHub, LeetCode

The hero leads with a small architecture diagram — `Frontend → API →
Database → Security` — instead of a photo, as a literal illustration of
"full-stack."

<br>

## ✨ Features

- 🎨 **Distinctive design** — blueprint/drafting-sheet visual language, not a template
- 📱 **Fully responsive** — clean down to a 360px mobile viewport
- ⚡ **Zero dependencies** — one HTML file, no npm install, no framework
- ♿ **Accessible** — visible keyboard focus, semantic structure, respects reduced-motion
- 🅰️ **Considered typography** — Space Grotesk, IBM Plex Sans, IBM Plex Mono

<br>

## 🚀 Running locally

Just open the file — no server required:

```bash
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or serve it (avoids any local file/CORS quirks):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

<br>

## 📤 Pushing to GitHub

If this is your **first time** setting Git up on this machine:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Then, from inside the project folder:

```bash
# 1. Turn the folder into a git repo
git init

# 2. Stage and commit everything
git add .
git commit -m "Initial commit: portfolio site"

# 3. Rename the default branch to main (skip if already on main)
git branch -M main

# 4. Point it at your GitHub repo (create an empty one on github.com first,
#    without a README, then copy its URL here)
git remote add origin https://github.com/gokulraj0280/portfolio.git

# 5. Push
git push -u origin main
```

**No repo yet?** Create one in two clicks:
1. Go to [github.com/new](https://github.com/new)
2. Name it `portfolio` (or anything you like), leave it **empty** — don't
   initialize with a README, license, or `.gitignore`
3. Click **Create repository**, then copy the HTTPS URL it shows you for step 4 above

**Pushed to it before?** Just commit and push the update:

```bash
git add .
git commit -m "Update portfolio"
git push
```

> 💡 If `git push` asks for a password and rejects your normal GitHub
> password, GitHub needs a **Personal Access Token** instead — generate one
> under **Settings → Developer settings → Personal access tokens**, and paste
> it in place of the password. Alternatively, set up an SSH key and use
> `git@github.com:gokulraj0280/portfolio.git` as the remote URL instead.

<br>

## 🌍 Deploying to GitHub Pages

Once the code is pushed:

1. On your repo page, go to **Settings → Pages**
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`
3. Choose branch `main`, folder `/ (root)` → **Save**
4. GitHub publishes the site at `https://gokulraj0280.github.io/portfolio/`
   within a minute or two — refresh the Pages settings page for the exact link
5. Add that link to your GitHub profile bio, LinkedIn, and the top of this README

<br>

## 🎨 Customising

| Want to change… | Where |
|---|---|
| Colors, type, spacing | CSS custom properties in the `<style>` block, under `:root` |
| Section content | Directly in `index.html` — each section is commented (`<!-- PROJECTS -->`, etc.) |
| Hero diagram | Inline SVG inside `.hero-figure` — edit `<text>` labels or add a layer |
| Résumé download button | Add a PDF next to `index.html`, then add `<a class="btn btn-ghost" href="resume.pdf" download>Download résumé</a>` |

<br>

## 📬 Contact

| | |
|---|---|
| ✉️ Email | [gokulraj2804@gmail.com](mailto:gokulraj2804@gmail.com) |
| 📱 Phone | +91 70924 60173 |
| 💼 LinkedIn | [linkedin.com/in/gokulraj-s-2b0668259](https://www.linkedin.com/in/gokulraj-s-2b0668259) |
| 💻 GitHub | [github.com/gokulraj0280](https://github.com/gokulraj0280) |
| 🧩 LeetCode | [leetcode.com/u/Gokulraj_04](https://leetcode.com/u/Gokulraj_04/) |

<div align="center">
<sub>Drawn by Gokulraj S &nbsp;·&nbsp; Revision 2026 &nbsp;·&nbsp; Hosur, India</sub>
</div>
