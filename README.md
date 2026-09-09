# 🎨 Md Yusuf — 3D Interactive Portfolio

A stunning, immersive 3D portfolio website built with **React**, **Three.js**, and **React Three Fiber**. Walk through a hand-drawn sketch-style corridor, enter doors to explore different rooms — About, Gallery, Studio, and Contact.

![Portfolio Preview](https://img.shields.io/badge/Live-Portfolio-blueviolet?style=for-the-badge)

---

## ✨ Features

- 🚪 **Interactive 3D Entrance** — Click the doors to enter a fully navigable corridor
- 🎨 **Hand-Drawn Sketch Aesthetic** — Every element uses a unique paper/sketch art style
- 🏠 **Multiple Rooms** — About, Gallery (Projects), Studio (Social/Content), Contact
- 📱 **Fully Responsive** — Works on desktop, tablet, and mobile with touch/gyroscope support
- 🗺️ **Teleport Navigation** — Quick-travel map to jump between rooms
- 🔊 **Spatial Audio** — 3D positional sound effects for door opens, ambient music
- 🎭 **Animated Avatar** — 9-frame cartoon character animation with physics-based dodge
- 📧 **Contact Form** — Direct mailto integration for messages
- 🏆 **Achievement System** — Hidden achievements for exploring the portfolio
- ⚡ **Performance Optimized** — Adaptive quality tiers, texture preloading, shader warm-up

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Frontend** | React 19, JavaScript (ES6+) |
| **3D Engine** | Three.js, React Three Fiber, Drei |
| **Animation** | GSAP, CSS Animations |
| **Styling** | SCSS, CSS Custom Properties |
| **Build Tool** | Vite 8 |
| **Deployment** | Vercel |

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/mdyusuf0/My-Portfolio.git

# Navigate to project directory
cd My-Portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

### Build for Production

```bash
npm run build
```

The production bundle will be generated in the `dist/` directory.

---

## 📁 Project Structure

```
src/
├── components/
│   ├── canvas/           # 3D components (Three.js)
│   │   ├── corridor/     # Infinite corridor, avatar, doors
│   │   ├── entrance/     # Entrance doors, sign system
│   │   └── rooms/        # About, Gallery, Studio, Contact rooms
│   ├── dom/              # DOM overlay components (preloader, transitions)
│   └── ui/               # Navigation UI, overlays
├── context/              # React contexts (Scene, Audio, Performance)
├── hooks/                # Custom hooks (camera, document meta)
├── config/               # Texture preload lists, configuration
├── styles/               # SCSS stylesheets
└── utils/                # Utility functions
```

---

## 🎯 Rooms Overview

| Room | Description |
|------|-------------|
| **About** | Story milestones, capability cards, flying sky certificates |
| **Gallery** | Project showcase — Karigar, OmniServe, AI Sentiment Intelligence |
| **Studio** | Social media & content — LinkedIn, GitHub, Instagram, Resume |
| **Contact** | 3D barrel links, message paper, mailto form |

---

## 👤 About Me

**Md Yusuf** — Full-Stack Developer specializing in Java, Spring Boot, MERN Stack, and Python.

- 🎓 B.Tech CSE | IES College of Technology, Bhopal (8.5 CGPA)
- 💼 Intern @ Netlink Software Pvt. Ltd.
- 🏅 IIT Roorkee Full-Stack Bootcamp Certified
- 🏆 Technocrats Hackathon Winner

### Connect

- 🔗 [LinkedIn](https://linkedin.com/in/mdyusuf0)
- 💻 [GitHub](https://github.com/mdyusuf0)
- 📷 [Instagram](https://instagram.com/heyyusuffff)
- 📧 mdyusufcse096@iesuniversity.ac.in
- 📄 [Resume](https://drive.google.com/file/d/1ObdGWtVSx8SsfR4AcbCySSd9LFXcAs9f/view?usp=sharing)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  Built with ❤️ by <a href="https://github.com/mdyusuf0">Md Yusuf</a>
</p>
