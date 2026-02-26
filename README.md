# SkyDiscover Website

Website for **SkyDiscover** — a flexible framework for AI-driven scientific and algorithmic discovery from [UC Berkeley Sky Lab](https://sky.cs.berkeley.edu/).

## Local Development

```bash
# Clone the repo
git clone https://github.com/skydiscover-ai/skydiscover-ai.github.io.git
cd skydiscover-ai.github.io

# Start a local server (Python 3)
python3 -m http.server 8080

# Or use Node
npx serve .
```

Open [http://localhost:8080](http://localhost:8080) in your browser.

## Project Structure

```
├── index.html       # Landing page
├── blog.html        # Blog post
├── papers.html      # Research papers
├── style.css        # Shared stylesheet
├── assets/
│   ├── logo.png           # Full logo with text
│   ├── logo_vector.png    # Clean vector icon (favicon + nav)
│   └── blog/              # Blog images & media
└── README.md
```

## Deploying to GitHub Pages

This site is deployed automatically via GitHub Pages from the `main` branch.

**Steps to publish changes:**

1. Make your edits locally and preview with the local server
2. Stage and commit your changes:
   ```bash
   git add index.html style.css papers.html blog.html
   git commit -m "Update website"
   ```
3. Push to the `main` branch:
   ```bash
   git push origin main
   ```
4. GitHub Pages will automatically build and deploy within a few minutes
5. Visit [https://skydiscover-ai.github.io](https://skydiscover-ai.github.io) to see the live site

**GitHub Pages settings** (one-time setup):
- Go to **Settings > Pages** in the repository
- Set **Source** to "Deploy from a branch"
- Set **Branch** to `main` and folder to `/ (root)`
- Click **Save**

## Features

- Light / dark theme toggle (persisted in localStorage)
- Responsive design (mobile, tablet, desktop)
- Berkeley Blue + California Gold color scheme
- Frosted glass navigation bar
- Collapsible abstracts on paper cards
