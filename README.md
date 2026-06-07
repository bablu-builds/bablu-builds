<div align="center">

  <!-- Animated Header -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00e5e0,50:00d084,100:8b5cf6&height=200&section=header&text=Bablu%20Chaudhary&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Personal%20Portfolio%20%7C%20React%20%2B%20TypeScript%20%2B%20Vite&descSize=18&descAlignY=60" />

  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/badge/React-19.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React" />
    <img src="https://img.shields.io/badge/TypeScript-5.9.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Vite-7.2.4-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
    <img src="https://img.shields.io/badge/Tailwind-3.4.19-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
    <img src="https://img.shields.io/badge/GSAP-3.15.0-88CE02?style=for-the-badge&logo=greensock&logoColor=white" alt="GSAP" />
  </p>

  <p>
    <a href="https://github.com/bablu-builds">
      <img src="https://img.shields.io/github/followers/bablu-builds?label=Follow&style=social" alt="GitHub Followers" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=bablu-builds&color=00e5e0&style=flat-square" alt="Profile Views" />
  </p>

  <h3>🚀 A modern, animated personal portfolio website</h3>

  <p>
    <a href="https://github.com/bablu-builds"><strong>🔗 Live Demo</strong></a> •
    <a href="#-features"><strong>✨ Features</strong></a> •
    <a href="#-tech-stack"><strong>🛠️ Tech Stack</strong></a> •
    <a href="#-getting-started"><strong>🚀 Getting Started</strong></a>
  </p>

</div>

---

## 📸 Preview

<div align="center">

| **Hero Section** | **About & Skills** |
|:---:|:---:|
| Animated typewriter effect with particle background | Interactive skill bars with GSAP scroll animations |

| **Projects** | **Cyber Security Journey** |
|:---:|:---:|
| Card-based project showcase with hover effects | Animated roadmap timeline with phase indicators |

| **Contact** |
|:---:|
| Terminal-style typing animation with social links |

</div>

> 💡 **Note:** Replace this section with actual screenshots by adding images to `/public/images/` and updating the links above.

---

## ✨ Features

### 🎨 Design & Animation
- **Particle Canvas Background** — Interactive particle network with mouse repulsion effect
- **GSAP Scroll Animations** — Smooth entrance animations for all sections
- **Typewriter Effect** — Auto-typing role switcher in the hero section
- **Terminal Typing Animation** — Command-line style contact section
- **Responsive Design** — Fully mobile-friendly with hamburger menu

### 📄 Sections
| Section | Description |
|---------|-------------|
| **Hero** | Name, animated role text, location, CTA buttons |
| **About** | Bio with animated stat cards (10+ Projects, 5+ Technologies, etc.) |
| **Skills** | Animated progress bars for Languages, Tools, AI/ML, Cyber Security |
| **Projects** | 3 featured projects with tags, descriptions, and GitHub links |
| **Cyber Journey** | 5-phase roadmap from Linux basics to AI-powered security tools |
| **Contact** | Social links + terminal-style info block |

### 🧩 UI Components
- **40+ shadcn/ui components** pre-installed (Button, Card, Dialog, Form, Table, etc.)
- **Lucide React icons** throughout
- **Custom gradient themes** (Cyan `#00e5e0` + Green `#00d084` + Purple `#8b5cf6`)

---

## 🛠️ Tech Stack

### Core Framework
| Technology | Version | Purpose |
|------------|---------|---------|
| [React](https://react.dev/) | 19.2.0 | UI Library |
| [TypeScript](https://www.typescriptlang.org/) | ~5.9.3 | Type Safety |
| [Vite](https://vitejs.dev/) | 7.2.4 | Build Tool & Dev Server |

### Styling & UI
| Technology | Version | Purpose |
|------------|---------|---------|
| [Tailwind CSS](https://tailwindcss.com/) | 3.4.19 | Utility-first CSS |
| [shadcn/ui](https://ui.shadcn.com/) | — | 40+ accessible UI components |
| [Lucide React](https://lucide.dev/) | 0.562.0 | Icon library |
| [class-variance-authority](https://cva.style/) | 0.7.1 | Component variant management |
| [tailwind-merge](https://github.com/dcastil/tailwind-merge) | 3.4.0 | Tailwind class merging |

### Animation
| Technology | Version | Purpose |
|------------|---------|---------|
| [GSAP](https://greensock.com/gsap/) | 3.15.0 | Advanced scroll & entrance animations |
| [ScrollTrigger](https://greensock.com/scrolltrigger/) | (included) | Scroll-based animation triggers |

### Form & Validation
| Technology | Version | Purpose |
|------------|---------|---------|
| [React Hook Form](https://react-hook-form.com/) | 7.70.0 | Form management |
| [Zod](https://zod.dev/) | 4.3.5 | Schema validation |
| [@hookform/resolvers](https://github.com/react-hook-form/resolvers) | 5.2.2 | Form resolvers |

### Additional Libraries
- **react-router** 7.6.1 — Client-side routing
- **recharts** 2.15.4 — Data visualization charts
- **embla-carousel-react** 8.6.0 — Touch carousel
- **sonner** 2.0.7 — Toast notifications
- **date-fns** 4.1.0 — Date formatting
- **next-themes** 0.4.6 — Theme management

---

## 📁 Project Structure

```
my-app/
├── public/
│   └── images/              # Project screenshots & assets
├── src/
│   ├── components/
│   │   ├── Navbar.tsx       # Fixed navigation with scroll spy
│   │   ├── Footer.tsx       # Site footer with social links
│   │   ├── ParticleCanvas.tsx # Interactive particle background
│   │   └── ui/              # 40+ shadcn/ui components
│   ├── sections/
│   │   ├── Hero.tsx         # Landing section with typewriter
│   │   ├── About.tsx        # Bio + animated stat cards
│   │   ├── Skills.tsx       # Skill bars with scroll animation
│   │   ├── Projects.tsx     # Project showcase cards
│   │   ├── CyberJourney.tsx # Security roadmap timeline
│   │   └── Contact.tsx      # Terminal-style contact section
│   ├── hooks/
│   │   └── use-mobile.ts    # Mobile detection hook
│   ├── App.tsx              # Root component
│   ├── App.css              # App-specific styles
│   ├── index.css            # Global styles & Tailwind directives
│   └── main.tsx             # Entry point
├── index.html               # HTML entry point
├── vite.config.ts           # Vite configuration
├── tailwind.config.js       # Tailwind theme & plugins
├── postcss.config.js        # PostCSS configuration
├── tsconfig.json            # TypeScript config
├── components.json          # shadcn/ui configuration
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) 20+ (recommended)
- [npm](https://www.npmjs.com/) or [pnpm](https://pnpm.io/) or [yarn](https://yarnpkg.com/)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/bablu-builds/portfolio.git
cd portfolio

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
```

The app will be available at **`http://localhost:5173`**

---

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with HMR |
| `npm run build` | Build for production (TypeScript compile + Vite build) |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint for code quality checks |

---

## 🌐 Deployment

### Option 1: GitHub Pages (Free)
```bash
# Build the project
npm run build

# The `dist/` folder contains the static files ready for deployment
# Upload `dist/` contents to your GitHub Pages branch
```

### Option 2: Vercel (Recommended)
1. Push code to GitHub
2. Import repo on [vercel.com](https://vercel.com)
3. Framework preset: **Vite**
4. Build command: `npm run build`
5. Output directory: `dist`
6. Deploy! 🎉

### Option 3: Netlify
- Drag & drop the `dist/` folder to [Netlify Drop](https://app.netlify.com/drop)

---

## 🎨 Customization Guide

### 1. Update Personal Info
Edit these files to add your details:

| File | What to Change |
|------|----------------|
| `index.html` | `<title>` and `<meta name="description">` |
| `src/sections/Hero.tsx` | Name, roles, location |
| `src/sections/About.tsx` | Bio text, stats numbers |
| `src/sections/Contact.tsx` | Social links, email |
| `src/components/Footer.tsx` | Brand name, GitHub link |

### 2. Update Projects
Edit `src/sections/Projects.tsx`:
```typescript
const projects = [
  {
    number: '// PROJECT_01',
    title: 'Your Project Name',
    description: 'Project description...',
    image: '/images/your-screenshot.jpg',
    tags: ['React', 'TypeScript', 'Tailwind'],
    link: 'https://github.com/bablu-builds/your-repo',
  },
  // ...add more
];
```

### 3. Update Skills
Edit `src/sections/Skills.tsx` to match your actual skill levels.

### 4. Add Project Images
Place screenshots in `public/images/` and reference them as `/images/filename.jpg`.

### 5. Update Cyber Security Journey
Edit `src/sections/CyberJourney.tsx` to reflect your actual learning path.

---

## 🔗 Social Links (Update These!)

The following links in the code are placeholders — **update them with your real profiles**:

| Platform | Current | Update In |
|----------|---------|-----------|
| GitHub | ✅ `https://github.com/bablu-builds` | Working |
| LinkedIn | ❌ `https://linkedin.com` | `src/sections/Contact.tsx` |
| Twitter/X | ❌ `https://twitter.com` | `src/sections/Contact.tsx` |
| Email | ❌ `mailto:contact@bablu.dev` | `src/sections/Contact.tsx` |

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a suggestion:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

<div align="center">

  **Bablu Chaudhary**

  <p>
    <a href="https://github.com/bablu-builds">
      <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
    </a>
    <a href="https://linkedin.com/in/YOUR_LINKEDIN">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" />
    </a>
    <a href="mailto:YOUR_EMAIL@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" />
    </a>
  </p>

  <sub>Built with ❤️ using React + TypeScript + Vite + Tailwind + GSAP</sub>

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00e5e0,50:00d084,100:8b5cf6&height=120&section=footer" />
</div>
