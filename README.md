# PortfoliCraft — Professional Portfolio Builder & Link Generator

**PortfoliCraft** is an interactive, zero-setup web application that allows you to configure your professional portfolio in real-time, view live changes side-by-side, and **generate an instant shareable website link** or **export a standalone HTML file**.

No backend, database, or build tools required — everything works entirely client-side in the browser!

---

## 🌟 Key Features

1. **Two-Column Interactive Workspace**:
   - **Left Column (Editor)**: Clean, collapsible input forms for every section of your portfolio.
   - **Right Column (Live Preview)**: Instantaneous real-time preview of your portfolio as you type.

2. **Extensive Data Customization**:
   - **Personal & Hero**: Name, professional title, headline tagline, location, email, avatar image (upload local file or paste URL), and "Available for work" status badge.
   - **Social & Resume**: GitHub, LinkedIn, Twitter/X, and direct Resume/CV download link.
   - **About & Key Metrics**: Markdown-ready extended bio, plus custom metric highlight cards (e.g. Years of Experience, Delivered Projects, Client Rating).
   - **Skills Taxonomy**: Grouped into Frontend Architecture, Backend & Databases, and Cloud/DevOps/AI with responsive tags.
   - **Dynamic Projects Showcase**: Add unlimited projects with cover image, tags, descriptions, live demo links, and GitHub repository links.
   - **Work Experience Timeline**: Interactive career timeline with roles, companies, dates, locations, and achievements.
   - **Education & Credentials**: Degrees, universities, graduation years, and certifications.

3. **Instant Website Link Generation**:
   - Click **"Share Link"** to compress and encode your entire portfolio profile into a URL fragment.
   - Anyone opening your unique link will see your customized, responsive portfolio loaded directly in presentation mode.
   - Zero database needed — your data is securely self-contained in the link itself!

4. **Standalone HTML Export**:
   - Click **"Export HTML"** to download a single self-contained `.html` file containing your portfolio.
   - Drag and drop it onto [Netlify Drop](https://app.netlify.com/drop), GitHub Pages, or Vercel for instant free global hosting.

5. **Aesthetics & Theming**:
   - **Accent Colors**: Switch instantly between Indigo, Emerald, Violet, Rose, Sky, and Amber palettes.
   - **Dark / Light Mode**: One-click toggle with smooth color transitions.
   - **Responsive View Modes**: Split View, Editor Only, and Fullscreen Live Presentation View.
   - **Auto-Save**: Automatically saves your work in `localStorage` so your progress is never lost.

---

## 🚀 How to Run

### Option 1: Direct Browser Launch
Simply double-click [`index.html`](file:///C:/Users/Shrinidhi%20S/.gemini/antigravity/scratch/portfolio-builder/index.html) in your file explorer to open it in Chrome, Edge, Brave, or Firefox.

### Option 2: Using Python's Built-in Server
Open PowerShell in this folder and run:
```powershell
python -m http.server 3000
```
Then visit:
[http://localhost:3000](http://localhost:3000)

### Option 3: Using Node / npx
```bash
npx serve .
```

---

## 🌐 How to Host Your Portfolio for Free

1. **GitHub Pages**:
   - Create a GitHub repository (e.g., `my-portfolio`).
   - Push `index.html` to the repository.
   - Go to **Settings > Pages** and select `main` branch. Your portfolio is live at `https://<username>.github.io/my-portfolio`!

2. **Netlify Drop**:
   - Go to [app.netlify.com/drop](https://app.netlify.com/drop).
   - Drag and drop this folder (`portfolio-builder`). Your portfolio will be live in 5 seconds with a custom HTTPS URL.

3. **Vercel**:
   - Run `npx vercel` in the project directory, or link your GitHub repo in the Vercel dashboard.
