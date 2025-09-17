## BuildElite — Services Website

A clean, responsive, single-page services/agency website built with plain HTML, CSS, and JavaScript. This repo contains the static site files only.

### ✨ Features
- **Responsive layout** for desktop, tablet, and mobile
- **Smooth scroll animations** via `ScrollReveal`
- **Lightweight, fast-loading** static assets
- **Easy to customize** (colors, content, images)

### 🖥️ Website Content
This site is a single-page layout with anchored navigation. Sections and their visible content:

- **Header / Navigation**: Brand `BuildElite` with links to `Home`, `About Us`, `Services`, `Projects`, `Contact Us`.

- **Home (Hero)**:
  - Title: “We Build What You Imagine.”
  - Description: “We provide the best home design, construction and maintenance services for you and your family.”
  - Buttons: `Our Services` (scrolls to Services) and `View Projects` (scrolls to Projects)
  - Quick stats: `13+ Years of Experience`, `400+ Complete Projects`
  - Background lines and two hero images.

- **About Us**:
  - Subtitle: `ABOUT US`
  - Title: “We Provide The Best Service To Build”
  - Description: Focus on providing top professionals to make your project a construction masterpiece.
  - Highlights list: Professional workers, Guaranteed quality, Extensive experience, We quote your project.
  - Button: `View Projects`
  - Two illustrative images.

- **Services** (Bootstrap carousel of cards):
  - Section heading: `OUR SERVICES` / “High Quality Construction Services”
  - Overview: “We provide multiple services for you, offering confidence and security in construction.”
  - CTA: `Contact Now`
  - Service cards include:
    - Housing Construction — “We build with the best professionals and high-quality work for a safe and effective home.”
    - Construction Of Home Areas — “We specialize in building residential spaces with a focus on quality, safety, and efficiency.”
    - Maintenance & Repair — “We offer comprehensive maintenance and repair solutions for all types of systems and equipment.”
    - Installation Of Ceramics — “We provide expert installation services for ceramics, tiles, and other materials.”
    - Water & Drainage — “Our expert team provides reliable water and drainage solutions.”

- **Projects** (latest completed):
  - Card 1: “Two Story House” — House construction — Date: October 15, 2024 — Description of structural construction elements.
  - Card 2: “Stairs & Columns” — Maintenance & Repair — Date: November 21, 2024 — Custom stairs and sturdy columns.
  - Card 3: “Kitchen Room” — Construction Of Home Areas — Date: December 28, 2024 — Functional and stylish kitchen space.

- **Contact**:
  - Subtitle: `CONTACT US` / Title: “Write To Us & Build”
  - Image and three contact cards:
    - Location: “thaltej cross road, ahmedabad”
    - Phone: `9999999999`, `9999988888`
    - Social chat links: WhatsApp, Messenger, Telegram

- **Footer**:
  - Brand: `BuildElite`
  - Tagline: “We build security and trust in homes.”
  - Email: `BuildElite123@gmail.com`
  - Quick links: About Us, Services, Projects
  - Info: Address (Thaltej cross road, Ahmedabad), Hours (9AM - 9PM)
  - Social: Facebook, Instagram, X (Twitter)
  - Copyright: “All Rights Reserved”

### 📁 Project Structure
```
BuildElite/
├─ index.html
├─ assets/
│  ├─ css/
│  │  └─ styles.css
│  ├─ js/
│  │  ├─ main.js
│  │  └─ scrollreveal.min.js
│  └─ img/
│     ├─ about-img-1.jpg
│     ├─ about-img-2.webp
│     ├─ contact-img.jpg
│     ├─ favicon.png
│     ├─ home-img-1.jpg
│     ├─ home-img-2.jpg
│     ├─ home-lines-bg.svg
│     ├─ projects-img-1.webp
│     ├─ projects-img-2.avif
│     └─ projects-img-3.png
```

### 🚀 Getting Started (Local)
- Option 1: Double-click `index.html` to open it in your browser.
- Option 2 (recommended for dev): Use a local server for proper asset caching and routing.
  - VS Code → install "Live Server" → Right-click `index.html` → "Open with Live Server".

### 🔧 Customization
- **Content**: Edit sections directly in `index.html` (hero, about, services, projects, contact).
- **Styles**: Adjust colors, spacing, and components in `assets/css/styles.css`.
- **Images**: Replace files in `assets/img/` with your own (keep names or update `<img>` paths).
- **Animations**: Tweak or remove reveal effects in `assets/js/main.js` and `assets/js/scrollreveal.min.js` usage.


### 🧪 Browser Support
Modern evergreen browsers (Chrome, Edge, Firefox, Safari). IE is not supported.

### 📜 License
This project is provided as-is for learning and portfolio use.

