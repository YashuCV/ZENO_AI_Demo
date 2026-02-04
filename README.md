# Zeno – AI Assistant Demo

A short demo of the Zeno AI Assistant project, hosted on GitHub Pages.

## View the demo

After you enable GitHub Pages (see below), the demo will be available at:

**`https://<your-username>.github.io/<repo-name>/`**

Example: `https://jane.github.io/zeno-ai-assistant/`

---

## Publish on GitHub Pages

### 1. Create a GitHub repository

- Go to [github.com/new](https://github.com/new).
- Name the repo (e.g. `zeno-ai-demo` or `Zeno-AI-Assistant`).
- Do **not** add a README (you already have one). Create the repo.

### 2. Push this folder to the repo

In Terminal, from this project folder:

```bash
cd "/Users/osuappcenter/Desktop/CV/Projects/Demo Links/Zeno - AI Assistant"

# Initialize git (if not already)
git init

# Add everything (index.html, README.md, and the .mov file)
git add .
git commit -m "Add demo page for GitHub Pages"

# Add your repo as remote (replace with your actual repo URL)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push
git branch -M main
git push -u origin main
```

### 3. Turn on GitHub Pages

- In the repo on GitHub: **Settings → Pages**.
- Under **Source**, choose **Deploy from a branch**.
- Branch: **main**, folder: **/ (root)**.
- Click **Save**.

After a minute or two, your site will be live at:

**`https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`**

---

## Video format note

The page uses your **.MP4** file. Many browsers support it. If someone has trouble playing it (e.g. in Firefox), you can:

1. Convert the video to **Desired extension)** (e.g. with QuickTime: File → Export → 1080p, or HandBrake).
2. Replace the file and in `index.html` change the `<source>` to point to the new `Desired extension` file.

---

## Repo size

GitHub has a **100 MB** per-file limit. If your file is larger, compress it or convert to a smaller MP4 before pushing.
