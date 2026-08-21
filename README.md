# The Phoenix Guide — CCS GC Roadmap

> **PHOENIX.EXE** — *Execute. Upgrade. Excel.*

An independent student-made enrollment guide for **College of Computer Studies (CCS)** applicants at **Gordon College, Olongapo City**. A static front-end site showcasing the school, the CCS program, a year-by-year IT roadmap, student tips, and a contact section.

---

## 📌 About

This is a single-page style guide built to help prospective and incoming CCS students at Gordon College understand:

- � Gordon College and the CCS program
- 🗺️ A roadmap for the IT/Computing curriculum (BSCS / BSIT / BSEMC)
- 💡 Tips for surviving and thriving in CCS
- 📬 Contact information for inquiries

> ⚠️ **Disclaimer:** This website is an *independent student-made enrollment guide* for CCS applicants of Gordon College. Official requirements, schedules, and policies are still subject to confirmation from the college administration.

---

## Pages

| Page | Purpose |
|---|---|
| `index.html` | Main landing page — home, GC overview, CCS program, roadmap, tips, contact |
| `admin.html` | Admin login page (static UI only) |

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — single stylesheet (`css/styles.css`), Google Fonts (Poppins), gradient/blur effects, animations
- **Vanilla JavaScript** — mobile hamburger menu and interactions
- **Static assets** — local images (`images/`) and a background video (`video/gc-vid.mp4`)
- **No build step** — just open `index.html` in a browser

---

## 📁 Project Structure

```
CCS_HUB/
├── index.html              # Main landing page
├── admin.html              # Admin login UI
├── css/
│   └── styles.css          # All site styles
├── images/                 # Logos, photos, backgrounds, icons
│   ├── ccs_logo.png
│   ├── GC.png
│   ├── BSIT.png / BSCS.png / BSEMC.png
│   ├── CLASS1.jpg / CLASS2.jpg
│   └── ... (more)
---

## Running Locally

This is a static site — no dependencies, no build step.

```bash
# Option 1: open directly
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux

# Option 2: serve with any static server (recommended for the video)
npx serve .
---

## Design System

- **Primary gradient:** Gordon College gold `#C99F2E` → dark gold `#8B6B1F` → CCS green `#1A472A`
- **Typography:** Poppins (Google Fonts) — weights 100–700
- **Layout:** Sticky navbar, hero section, sectioned content with anchor navigation
- **Mobile:** Hamburger off-screen menu, responsive typography

---

## Contributing

This is a student project. Suggestions and improvements are welcome:

1. Fork the repo
2. Create a branch (`git checkout -b feature/improvement`)
3. Commit your changes
4. Push and open a Pull Request

---

## Disclaimer & Credits

- Built by a Gordon College CCS student for prospective and incoming CCS students.
- **Not affiliated with or endorsed by** Gordon College administration. Official information should be confirmed directly with the college.
- Logos and images are property of their respective owners.

---

*Made in Olongapo City*

---
