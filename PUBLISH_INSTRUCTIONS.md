# How to Publish These Changes

## 1. GitHub Profile README (https://github.com/InfoSage05)

Where GitHub reads it from:
- A special public repository with the **same name as your username** (`InfoSage05`).
- The file must be named `README.md` at the root of that repo.

Steps:
1. Go to GitHub and create a new public repository called `InfoSage05`.
2. Do **not** initialize it with a license or .gitignore (you can add those later).
3. Copy the entire contents of `GITHUB_PROFILE_README.md` from this folder.
4. Paste it into the new repo as `README.md` and commit.
5. Visit `https://github.com/InfoSage05` — the new README should appear below your profile header.

> Tip: The GitHub profile README is purely Markdown. You can edit it directly on GitHub or locally and push.

---

## 2. Portfolio Website (https://infosage05.github.io/my-portfolio/)

Where the site is built from:
- This repo (`E:\Machine Learning\Portfolio`) is the source for `infosage05.github.io/my-portfolio/`.
- The file you need is `index.html` in this folder.

Steps:
1. Make sure this repo is connected to your GitHub repo `InfoSage05/my-portfolio`.
2. Commit the updated `index.html`:
   ```bash
   git add index.html
   git commit -m "Redesign portfolio with Linux terminal theme and tabbed sections"
   git push origin main
   ```
3. GitHub Pages will rebuild the site in about 30–60 seconds.
4. Visit `https://infosage05.github.io/my-portfolio/` to see the changes.

> Note: I cannot push to GitHub for you because I don't have your GitHub credentials. You need to commit and push these files yourself.

---

## Files Changed

| File | Purpose |
|------|---------|
| `index.html` | Linux-themed portfolio website with tabbed Projects / Open Source / Experience / Achievements / Skills / Contact sections |
| `GITHUB_PROFILE_README.md` | Content for your GitHub profile README (terminal style) |
| `PUBLISH_INSTRUCTIONS.md` | This file |

---

## What Was Included from the PDFs

- CGPA updated to **8.41**.
- Degree clarified: B.Tech. (Hons.) Manufacturing Science & Engineering + M.Tech. Industrial Engineering & Management, Micro Specialization in AI & Applications.
- Added **Experience** tab with:
  - UCD Ireland research internship (PostGIS + LightGBM + LLM agent pipeline)
  - vLLM open-source contributions (FP8 MLA KV-cache, scheduler bug, unit tests)
  - Unsloth AI open-source contributions (Triton kernels, LoRA bug, multi-GPU padding)
  - Nirveon X AI/ML internship
- Added **2026 achievements**:
  - General Championship Data Analytics 2026 — Frammer AI (4th place)
  - Flipkart Gridlock Hackathon 2.0 — Cognitive Traffic Orchestrator
  - Qwen Cloud Global AI Hackathon — QwenSwarm RepoPilot
- Updated project descriptions with metrics (3,500ms latency reduction, 83.3% cache hit rate, 8,000+ incidents, 1ms brief latency, etc.).
- Expanded skills section with SGLang, vLLM, Unsloth, LightGBM, OpenRouter, CrewAI, Keras, AWS, etc.

---

## Optional: GitHub Profile README Special Repo

If you already have a repo named `InfoSage05`:
- Open it on GitHub.
- Click `README.md` → Edit.
- Replace the contents with `GITHUB_PROFILE_README.md`.
- Commit the change.

If you want to preview it before committing, you can use the GitHub preview button while editing.
