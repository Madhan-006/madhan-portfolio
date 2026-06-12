# Madhan Kumar — Terminal Portfolio

A single-file HTML portfolio website with a dark hacker OS / terminal aesthetic — featuring a BIOS boot sequence, live clock, glitch hero title, typing terminal, animated skills grid, experience timeline, projects grid, and an interactive contact terminal.

🔗 Live demo: [maddyfx.lovable.app](https://maddyfx.lovable.app)

---

## ✨ Features

- **BIOS Boot Screen** — simulated startup log before the site loads
- **OS-style Navbar** — sticky nav bar with traffic-light dots and a live clock
- **Glitch Hero** — animated glitch-text title with a typing terminal effect
- **Skills Grid** — animated progress bars that fill in on scroll
- **Experience Timeline** — internship, hackathon, publication & education history
- **Projects Grid** — featured project cards
- **Interactive Contact Terminal** — type commands like `help`, `whoami`, `skills`, `contact`, `resume`, `sudo`, `clear`

---

## 🛠️ Tech Stack

- Pure **HTML, CSS & JavaScript** — no frameworks, no build step
- All CSS and JS are **inline in a single file**
- Fonts via Google Fonts:
  - [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) — terminal/code text
  - [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) — display/headings
  - [Oxanium](https://fonts.google.com/specimen/Oxanium) — UI/labels

---

## 📂 File Structure

```
.
└── index.html   ← the entire site (HTML + CSS + JS)
```

That's it — one file, no dependencies to install.

---

## 🚀 Running Locally

Since it's a single static HTML file, you can run it without any setup:

1. Download/clone this repo
2. Open `index.html` directly in your browser

   *or* serve it locally for a more "real" experience:

   ```bash
   # Python 3
   python -m http.server 8000
   ```

   then visit `http://localhost:8000`

---

## 🌍 Deployment

Any static hosting works. A few free options:

### GitHub Pages
1. Push this repo to GitHub
2. Rename the HTML file to `index.html` (if not already)
3. Go to **Settings → Pages** → set source to `main` branch, root folder
4. Site goes live at `https://<your-username>.github.io/<repo-name>`

### Netlify Drop
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop `index.html` onto the page
3. Get an instant live URL

### Vercel / Cloudflare Pages
Connect this repo and deploy — both support custom domains for free.

---

## ✏️ Customization

All content lives in `index.html`:

| Section | What to edit |
|---|---|
| **Boot sequence** | `bootLog` array in the `<script>` section |
| **Hero typing lines** | `typingStrings` array |
| **Skills** | `.skill-card` blocks in the Skills section (adjust `--w` for bar %) |
| **Experience / Education** | `.tl-item` blocks in the Experience timeline |
| **Projects** | `.project-card` blocks in the Projects grid |
| **Contact info & terminal commands** | Contact section + `responses` object in the script |
| **Colors** | CSS variables at the top of `<style>` (`--green`, `--cyan`, `--amber`, `--bg`, etc.) |

---

## 📬 Contact

- **Email:** maddyfx006@gmail.com
- **Phone:** +91 8124016941
- **LinkedIn:** [linkedin.com/in/madhan-analyst](https://www.linkedin.com/in/madhan-analyst)
- **Portfolio:** [maddyfx.lovable.app](https://maddyfx.lovable.app)

---

## 📄 License

Free to use and adapt for your own portfolio. Attribution appreciated but not required.
