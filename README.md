# 🌌 Nizam Bajud - 3D Animated Portfolio Website

A cutting-edge, professional portfolio website crafted for **Nizam Bajud**, featuring an interactive 3D WebGL neural particle constellation & cyber core, glassmorphic UI, audio feedback, and full resume integration.

---

## 🚀 Key Features

1. **Interactive 3D WebGL Background (`Three.js`)**:
   - Dynamic 3D neural network constellation where nodes connect dynamically based on proximity.
   - Central wireframe **Data Core** (Icosahedron & pulsating nucleus) orbiting in real-time.
   - Mouse parallax tracking and interactive energy shockwave on mouse click.
   - Scroll-driven camera trajectory smoothly shifting perspective through sections.
   - Automatic 2D Canvas fallback engine ensuring 100% reliability on any hardware.

2. **Tailored Directly From Nizam's Resume**:
   - **Hero Section**: Dynamic typewriter text showcasing *Data Analytics Specialist*, *BCA Student @ Dr. Subhash University*, *L&T Program Rank 1*, and *AI Enthusiast*.
   - **Academic Timeline**:
     - **BCA (Pursuing, 2028 Batch)** at Dr. Subhash University with current **9.10 SGPA** and L&T Data Analytics specialization.
     - **Class 12 Higher Secondary (2025)** with **90.1% Distinction**.
     - **Class 10 Secondary School (2023)** with **66%**.
   - **Technical Skills Matrix**: Interactive animated progress bars for C, C++, PHP, JavaScript ES6, MySQL, HTML5/CSS3/Bootstrap, and MS Excel Dashboards.
   - **Featured Projects**:
     - *Interactive Analytics Dashboard (Excel BI & Data Modeling)* with an interactive in-browser simulator!
     - *Library Space Utilization Software (C++, PHP, MySQL)* with real-time zone occupancy matrix preview.
   - **Honors & Achievements**: 1st Rank in Semester 1 (L&T), 1st Rank in Semester 2 (L&T), 3rd Rank in Semester 2 (College with 9.10 SGPA).
   - **Verified Certifications**: IBM AI & Machine Learning, Be10X AI Course, JavaScript ES6+.
   - **Contact & Communication**: One-click email drafter (`mailto:bajudnizam@gmail.com`), phone dialer (`+91 8200335213`), and clipboard copy.
   - **Official Declaration**: Includes Nizam's signature block and declaration citation directly from the resume.

3. **Extras & Polish**:
   - **3D HUD Engine Controls**: Floating button in bottom right to switch theme colors (*Cyan Nebula*, *Cyber Purple*, *Matrix Emerald*) and tweak rotation speeds.
   - **Web Audio API Sound FX**: Toggle subtle futuristic synthesizer chimes on button and link interactions.
   - **Integrated Resume Viewer**: Modal view of the original verified resume with download and print buttons.
   - **Ultra Responsive**: Optimized for desktops, tablets, and smartphones.

---

## 📁 File Structure

```
d:\portfolio_website\
│
├── index.html                   # Main single-page portfolio application
├── css\
│   └── styles.css               # Futuristic cyber dark theme & glassmorphic styles
├── js\
│   ├── three-scene.js           # Three.js 3D background engine & canvas fallback
│   └── main.js                  # Typewriter, modals, simulator, sound FX & form handler
├── assets\
│   └── nizam_bajud_resume.jpg   # Scanned resume asset for modal & downloads
└── README.md                    # Project documentation
```

---

## 🖥️ How to Run & View

### Option 1: Direct File Open
Simply double-click [`index.html`](file:///d:/portfolio_website/index.html) in your file explorer to open it directly in Chrome, Edge, Brave, or Firefox.

### Option 2: Local Web Server
You can run any local static server:
```powershell
# Using Python
python -m http.server 8080 --directory "d:\portfolio_website"

# Using Node.js
npx serve "d:\portfolio_website"
```
Then visit `http://localhost:8080/` in your browser.

---

## 🌐 Free 1-Click Deployment Options
- **GitHub Pages**: Push this directory to a GitHub repository, go to **Settings > Pages**, and choose the main branch.
- **Vercel / Netlify**: Drag-and-drop the `portfolio_website` folder directly into the Netlify/Vercel dashboard for an instant live URL.
