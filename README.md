# iPhone Website Clone

![Hero Preview](public/assets/images/hero.jpeg)

An elegant, high-fidelity clone of the Apple iPhone product site — built with React, Vite and Tailwind CSS. This project showcases crisp visuals, responsive layouts, immersive video sections and an embedded 3D model for realistic product presentation.

**Why this repo?**
- **Pixel-accurate UI**: Carefully styled components and smooth transitions for a modern product landing experience.
- **Interactive media**: Video hero sections, autoplay highlights, and an integrated `.glb` model for a realistic 3D preview.
- **Fast & lightweight**: Built with Vite for instant dev feedback and Tailwind for small, maintainable styles.

--

**Live Preview**

Open `index.html` in the repo or run locally to see the full experience.

![Frame preview](public/assets/images/frame.png)

--

**Features**
- Responsive, mobile-first design that mirrors a modern product landing page.
- Autoplaying hero video with controls and optimized video assets.
- Highlights carousel with looping media.
- 3D model viewer (`public/models/scene.glb`) integrated into the page for interactive rotation/zoom.
- Built with React + Vite + Tailwind CSS for a fast developer experience.

**Tech stack**
- React
- Vite
- Tailwind CSS
- JavaScript (ESModules)
- GLB model support (three.js / model-viewer style integration inside `src/components`)

--

**Quick Setup (Windows PowerShell)**

1. Install Node.js (recommended v18+). Then, from the repo root:

```powershell
# install dependencies
npm install

# start dev server (Vite)
npm run dev

# build for production
npm run build

# preview production build locally
npm run preview
```

2. Open the URL shown by Vite (usually `http://localhost:5173`) in your browser.

--

**Project structure (key files)**

- `index.html` — entry HTML and meta.
- `src/main.jsx` — React bootstrap.
- `src/App.jsx` — global app layout and routes.
- `src/components/` — UI building blocks (Hero, Navbar, ModelView, Highlights, VideoCarousel, etc.).
- `public/models/scene.glb` — 3D model used by the viewer.
- `public/assets/` — images & videos used across the site.
- `tailwind.config.js` — Tailwind configuration.
- `vite.config.js` — Vite configuration.

--

**Screenshots**

Hero section (video background):

![Hero Preview](public/assets/images/hero.jpeg)

Product frame / model area:

![Frame preview](public/assets/images/frame.png)

--

Tips & troubleshooting
- If videos don't autoplay, check browser autoplay settings — some browsers block sound-enabled autoplay.
- If the 3D model doesn't show, confirm `public/models/scene.glb` exists and is being served; check browser console for CORS or fetch errors.
- For build errors, ensure Node.js and npm are up to date and that dependencies installed correctly.

--

Contributing
- Fork the repo and open a PR for features, bug fixes, or accessibility improvements. Please include a screenshot or short recording for UI changes.

--

Deployment suggestions
- Deploy to Vercel or Netlify for a frictionless static deployment (both integrate well with Vite). Example: connect this GitHub repo and set the build command to `npm run build` and publish the `dist` folder.

--

License & contact
- This project is provided as-is. Add your preferred license file (`LICENSE`) if you intend to publish.
- Questions or want help polishing the README or adding CI/CD? Open an issue or contact the repo owner.

--

Enjoy — and tell me if you want a GIF hero, automated deploy config, or a `README` badge set added next.
