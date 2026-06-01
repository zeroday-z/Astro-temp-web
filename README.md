# AstroMP - The Framework For Creators ⚡

(AI generated, pls make sure to keep it updated time to time. Thx)

## 🚀 Features

- **Authentic GTA 5 Aesthetic:** Utilizes `Bebas Neue` typography, scanline effects, halftone dot patterns, and the iconic Rockstar `#f9c200` yellow.
- **Asymmetric Bento Layout:** Modern, data-dense feature presentations highlighting architecture and engine capabilities.
- **Live Terminal Animation:** An animated `server_console.exe` boot sequence showcasing the raw backend power.
- **Fully Modular Architecture:** The frontend is split into highly focused React components (`Hero`, `Features`, `CodeSection`, `Ticker`, `Footer`) making it effortlessly scalable for multiple developers.
- **High-Performance:** Built on Vite + React 18, utilizing CSS-driven animations to maintain a 0ms overhead feel and instant loads.

## 🛠 Tech Stack

- **Framework:** React 18
- **Build Tool:** Vite
- **Styling:** Tailwind CSS v4 + Native CSS animations
- **Icons:** Lucide React
- **Typography:** Bebas Neue, Inter, JetBrains Mono
- **Animations:** Framer Motion

## 💻 Local Development

To run the AstroMP website locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/daksh100sharma/Astro-MP-Website.git
   cd Astro-MP-Website
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   The site will be available at `http://localhost:5173`.

## 📂 Project Structure

```
Astro-MP-Website/
├── src/
│   ├── components/
│   │   ├── BootTerminal.tsx    # Animated server console
│   │   ├── CodeSection.tsx     # Framework API examples
│   │   ├── Features.tsx        # Bento Grid feature layout
│   │   ├── Footer.tsx          # Community links & copyright
│   │   ├── Hero.tsx            # Main hero header
│   │   ├── Navbar.tsx          # Sticky navigation
│   │   └── Ticker.tsx          # Infinite scrolling marquee
│   ├── App.tsx                 # Main layout assembler
│   ├── index.css               # Global styles & custom animations
│   └── main.tsx                # React mount point
└── package.json                # Project dependencies
```

## 🏗 Building for Production

To generate an optimized production build:

```bash
npm run build
```
This will output the compiled static assets into the `dist/` directory, ready to be deployed to any static host (Vercel, Netlify, Nginx, etc).

## 🤝 Contributing

This project is built to be easily extensible. All major sections are separated into their own component files inside `src/components/`. If you are adding a new section, simply create a new `.tsx` file in the components directory and import it into `App.tsx`.

---
*Not affiliated with Rockstar Games or Take-Two Interactive.*