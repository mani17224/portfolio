# 🚀 Mani Kumar Krovvidi — Personal Portfolio

> A modern, advanced single-file HTML portfolio with particle animations, 3D card effects, custom cursor, and a fully working contact form.

---

## 📸 Preview

```
Hero Section → About → Skills → Projects → Certifications → Contact
```

Built with pure **HTML**, **CSS**, and **Vanilla JavaScript** — no frameworks, no build tools, just one file.

---

## ✨ Features

### 🎨 Design & UI
- Deep obsidian dark theme with electric teal `#00F5CF` accent
- **Syne** display font + **DM Sans** body + **DM Mono** for labels
- Fully responsive — mobile, tablet, and desktop
- Custom glowing cursor with smooth lag-ring follow effect
- Animated atmospheric glow orbs in the background
- CSS grid lines overlay on the hero

### 🎬 Animations
- **Particle network canvas** on the hero (connected dots, GPU-smooth)
- **Typewriter** cycling through 5 roles
- **3D perspective tilt** on project cards (mouse-tracked)
- Animated **skill bars** that fill on scroll into view
- **Count-up stat numbers** in the About section
- Staggered **section reveal animations** (slide-up fade)
- Floating animated tags on the hero orb

### 🧭 Navigation
- Scroll **progress bar** at the top edge
- Fixed **navbar** that turns glassy on scroll with active link highlight
- Right-side **dot navigation** with label tooltips (desktop)
- **Mobile slide-in drawer** with hamburger animation
- **Back-to-top button** (appears after 500px scroll)
- **Preloader** screen on page load

### 📬 Contact Form
- Real email delivery via **Web3Forms** (works from local files & any hosting)
- Silent `fetch()` — page never redirects
- Client-side validation with toast notifications
- Sending state with spinner on button
- Direct `mailto:` email link alongside the form

---

## 🛠️ Tech Stack

| Layer      | Technology                              |
|------------|-----------------------------------------|
| Structure  | HTML5                                   |
| Styling    | CSS3 (Custom Properties, Grid, Flexbox) |
| Logic      | Vanilla JavaScript (ES6+)               |
| Icons      | Font Awesome 6                          |
| Fonts      | Google Fonts (Syne, DM Sans, DM Mono)   |
| Email      | Web3Forms API                           |
| Canvas     | HTML5 Canvas API (particle network)     |

---

## 📁 Project Structure

```
portfolio/
│
├── portfolio.html      ← Entire project (HTML + CSS + JS in one file)
└── README.md           ← This file
```

---

## ⚙️ Setup & Usage

### 1. Clone or Download
```bash
git clone https://github.com/mani17224/portfolio.git
cd portfolio
```
Or simply download `portfolio.html`.

### 2. Open Locally
Just double-click `portfolio.html` — it opens in any browser with no server needed.

### 3. Connect the Contact Form

1. Go to **[web3forms.com](https://web3forms.com)**
2. Enter your email → click **"Create Access Key"**
3. Open `portfolio.html` → find this line near the bottom:
   ```js
   const WEB3_KEY = 'YOUR_ACCESS_KEY';
   ```
4. Replace `YOUR_ACCESS_KEY` with your key → save → done ✅

---

## 🌐 Deployment

### Option 1 — Netlify Drop (Easiest)
1. Go to **[app.netlify.com/drop](https://app.netlify.com/drop)**
2. Drag and drop `portfolio.html`
3. Get a live URL instantly — free

### Option 2 — GitHub Pages
1. Push `portfolio.html` to a GitHub repo named `username.github.io`
2. Go to **Settings → Pages → Source → main branch**
3. Your site is live at `https://mani17224.github.io`

### Option 3 — Vercel
```bash
npm i -g vercel
vercel
```

---

## 🎨 Customisation

All personal content is clearly marked in the HTML. Search for these and update:

| What                  | Where to find                        |
|-----------------------|--------------------------------------|
| Your name             | `hero-name`, `nav-brand`, footer     |
| Roles / typewriter    | `roles` array in JS                  |
| About text            | `#about` section                     |
| Skill percentages     | `data-width` attributes              |
| Projects              | `#projects` section cards            |
| Certifications        | `#certifications` section            |
| Email address         | `contact-email-btn` href             |
| Social links          | `hero-socials` + `contact-socials`   |
| Accent color          | `--accent: #00F5CF` in `:root`       |
| Web3Forms key         | `const WEB3_KEY` in JS               |

---

## 📄 Sections

| Section            | Description                                      |
|--------------------|--------------------------------------------------|
| **Hero**           | Name, typewriter role, CTA buttons, social links |
| **About**          | Bio, skill chips, animated stat counters         |
| **Skills**         | Animated progress bars + tech chip grid          |
| **Projects**       | 3D tilt cards with stack tags and links          |
| **Certifications** | Icon cards for each credential                   |
| **Contact**        | Email link + working contact form                |

---

## 📬 Contact

**Mani Kumar Krovvidi**
- 📧 [manikumarkrovvidi@gmail.com](mailto:manikumarkrovvidi@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/krovvidi-manikumar-576676249)
- 🐙 [GitHub](https://github.com/mani17224/)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Built with ❤️ by Mani Kumar Krovvidi</p>
