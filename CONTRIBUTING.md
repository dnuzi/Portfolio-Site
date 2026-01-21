# Contributing to A Nest Level Portfolio

Thank you for considering contributing to **A Nest Level Portfolio**! We're thrilled to have you join the journey in crafting stunning, performant portfolios inspired by the serene vibes of Sri Lanka's hill country. Whether you're fixing a bug, adding a killer animation, or suggesting a dark mode toggle, your input helps make this template even more magical. 🌿💻

This guide outlines how to get involved. By participating, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md) (feel free to create one if it doesn't exist yet!).

## 🚀 Getting Started

1. **Fork the Repo**:
   - Head to [the repo](https://github.com/dnuzi/Portfolio-Site) and click **Fork**.
   - Clone your fork: `git clone https://github.com/YOUR_USERNAME/danuzz-portfolio.git`.
   - Create a feature branch: `git checkout -b feature/amazing-idea`.

2. **Set Up Locally**:
   - Install deps: `npm install`.
   - Run dev server: `npm run dev`.
   - Test your changes at `http://localhost:5173`.

3. **Explore the Code**:
   - **HTML**: Core structure in `index.html`.
   - **CSS**: Custom styles + Tailwind in `src/main.css`.
   - **JS**: Animations & logic in `src/main.js`.
   - **Config**: Vite magic in `vite.config.js`.

## 📋 Contribution Types

We welcome all kinds of contributions! Here's what fits best:

| Type | Description | Label |
|------|-------------|-------|
| **🐛 Bug Fix** | Spot a glitch? (e.g., animation stutter on mobile) | `bug` |
| **✨ Feature** | New idea? (e.g., theme switcher or more work cards) | `enhancement` |
| **📖 Docs** | Improve README or add guides? | `documentation` |
| **🔧 Refactor** | Clean up code without changing behavior? | `refactor` |
| **🎨 Style** | Tweak designs or animations? | `design` |
| **🚀 Performance** | Optimize bundle size or scroll? | `performance` |

### Reporting Issues
- Open a [new issue](https://github.com/dnuzi/Portfolio-Site/issues/new).
- Use the template: Describe the problem, steps to reproduce, and screenshots/GIFs.
- Bonus: Suggest a fix! (We love proactive contributors.)

### Submitting Pull Requests (PRs)
1. **Make Changes**:
   - Commit atomically: `git commit -m "feat: add dark mode toggle"`.
   - Push: `git push origin feature/amazing-idea`.

2. **Open PR**:
   - Link to the issue (e.g., "Fixes #42").
   - Describe: What? Why? How tested?
   - Add screenshots/GIFs for visual changes.

3. **PR Guidelines**:
   - **Small & Focused**: One change per PR.
   - **Tested**: Run `npm run build` and `npm run preview`.
   - **No Breaking Changes**: Update without wrecking existing setups.
   - **Squash Commits**: We'll merge cleanly.

## 🏗 Development Workflow

### Code Style
- **JS**: ES modules, consistent with Prettier (run `npx prettier --write .`).
- **CSS**: Tailwind utilities first; custom only when needed.
- **HTML**: Semantic, accessible (e.g., alt texts, ARIA labels).
- **Commits**: Use conventional commits (e.g., `feat:`, `fix:`, `docs:`).

### Testing
- **Manual**: Browser dev tools for animations; Lighthouse for perf/accessibility.
- **Build Check**: `npm run build` should output a single, minified `index.html` (<1MB).
- **Edge Cases**: Test on mobile, dark mode, slow networks.

### Releasing
- Bump version in `package.json` (e.g., `npm version patch`).
- Tag & push: `git push --tags`.
- Update demo on Vercel/Netlify.

## 🤝 Community & Support

- **Discussions**: Join [GitHub Discussions](https://github.com/dnuzi/Portfolio-Site/discussions) for Q&A.
- **Stuck?**: Open an issue or DM on [YouTube](https://www.youtube.com/@MovaNest).
- **Shoutouts**: We feature contributors in releases – tag yourself!

## ❤️ Credits

This project stands on the shoulders of giants:
- **GSAP & Lenis**: For fluid animations.
- **Tailwind & Vite**: Powering the build.
- **Remix Icon**: Clean SVGs.
- **You!** – Every star, fork, and PR fuels the fire.

Built with love from Negombo, Sri Lanka. Let's code like a hill country breeze – calm, yet unstoppable. 🌊

---

**Happy Contributing!**  
*Danu'Zz & Kelum'Xz* | January 2026 Edition  

[Back to README](README.md) | [Issues](https://github.com/dnuzi/Portfolio-Site/issues)
