# 🚀 YouTube AI Growth Studio

> An all-in-one AI platform for YouTube creators: channel audits, trending topics finder, viral title generator, 1280×720 thumbnail canvas studio, SEO optimizer, competitor analyzer, and content planner.

---

## 🌟 Core Features

- **Module 1: YouTube Channel Audit**: Algorithmic health score (1–100), breakdown across 6 categories (SEO, Thumbnail packaging, Content quality, Retention, Upload cadence, Branding), and a 30-day weekly action plan.
- **Module 2: Daily Trending Topics Finder**: Surging topics filtered by country, niche, and video format with AI opportunity scores (60–99).
- **Module 3: AI Video Title Generator**: 10 categorized title variations with real-time mobile truncation safety check (<60 chars) and side-by-side title comparison.
- **Module 4: AI Thumbnail Studio**: 16:9 1280×720 HTML5 Canvas editor with text overlays, contrast shadows, sticker badges, YouTube desktop & mobile feed simulators, and 1-click PNG/JPG download.
- **Module 5: Video SEO Optimizer**: Structured descriptions, comma-separated YouTube Studio tags, video chapters with timestamps, and high-engagement pinned comments.
- **Module 6: Competitor Channel Analyzer**: Identify competitor vulnerabilities and uncover content gap opportunities to win viewers.
- **Module 7: AI Content Calendar**: 7, 15, or 30-day publishing calendar with workflow status tracking (Planned, Scripting, Filming, Editing, Ready, Published) and JSON export.
- **Module 8: Performance Analytics**: 28-day impression trajectories, CTR milestones, retention velocity, and RPM models.
- **Saved Projects Vault**: Persistent local storage vault to store, copy, and export created assets.
- **Standalone Single-File Edition**: Located in `public/youtube-ai-growth-studio.html` — double-click to open in Google Chrome directly without any server!

---

## 📦 How to Deploy to GitHub (Step-by-Step)

### Step 1: Create a New Repository on GitHub
1. Go to [GitHub.com](https://github.com) and log in.
2. Click the **`+`** icon in the top right corner and choose **New repository**.
3. Name your repository (e.g., `youtube-ai-growth-studio`).
4. Keep it **Public** (recommended for free GitHub Pages) or Private.
5. Do **not** check "Initialize with a README" (we already have one).
6. Click **Create repository**.

---

### Step 2: Push Your Code from Your Computer

Open your terminal or command prompt inside the project folder, and run:

```bash
# 1. Initialize Git repository
git init

# 2. Add all project files
git add .

# 3. Create initial commit
git commit -m "Initial commit: YouTube AI Growth Studio full application"

# 4. Rename default branch to main
git branch -M main

# 5. Connect to your GitHub repository (replace with your actual GitHub repo URL)
git remote add origin https://github.com/YOUR_USERNAME/youtube-ai-growth-studio.git

# 6. Push the code to GitHub
git push -u origin main
```

---

### Step 3: Activate Free GitHub Pages Hosting

This repository includes a pre-configured GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically builds and deploys your site to GitHub Pages!

1. In your GitHub repository, click on **Settings** (top tab).
2. On the left sidebar, click on **Pages**.
3. Under **Build and deployment** > **Source**, select **`GitHub Actions`**.
4. That's it! GitHub will automatically trigger the workflow and publish your site at:
   ```
   https://YOUR_USERNAME.github.io/youtube-ai-growth-studio/
   ```

---

## ⚡ Alternative Free Deployments (1-Click)

### Deploy to Vercel (Recommended for Full-Stack)
1. Go to [Vercel.com](https://vercel.com) and click **Add New Project**.
2. Import your GitHub repository (`youtube-ai-growth-studio`).
3. Set Environment Variable: `GEMINI_API_KEY` = Your Google AI Studio API key.
4. Click **Deploy**. Vercel will build and give you a live production URL in under 60 seconds!

### Deploy to Netlify
1. Go to [Netlify.com](https://netlify.com) and click **Import from Git**.
2. Select your repository.
3. Build command: `npm run build`, Publish directory: `dist`.
4. Click **Deploy Site**.

---

## 💻 Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

Visit `http://localhost:3000` in your browser.

---

## 🔑 Environment Variables

To enable server-side Google Gemini AI features:

Create a `.env` file in the root folder:
```env
GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
PORT=3000
```
Get your free Gemini API key from [Google AI Studio](https://aistudio.google.com/).

---

## 📄 Standalone Chrome File

Want to run this app on any computer without Node.js or terminal?
Simply double-click the file inside:
```
public/youtube-ai-growth-studio.html
```
It runs 100% standalone directly inside Google Chrome!
