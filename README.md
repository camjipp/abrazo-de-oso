# Abrazo De Oso Foundation Website

A minimal, mysterious, and elegant website for the Abrazo De Oso Foundation built with Astro.

## 🚀 Features

- **Modern Minimal Design**: Clean, sophisticated aesthetic with beautiful typography
- **Smooth Animations**: Scroll-triggered animations and parallax effects
- **Mysterious Atmosphere**: Gradient orbs and subtle interactions create an enigmatic feel
- **Fully Responsive**: Looks stunning on all devices
- **Custom Cursor**: Enhanced desktop experience with custom cursor (on larger screens)
- **SEO Optimized**: Built with Astro for excellent performance and SEO
- **Zero JS by Default**: Lightning-fast load times with Astro's static generation

## 📂 Project Structure

```
abrazo_de_oso/
├── public/
│   ├── scripts/
│   │   └── main.js       # Interactive features
│   └── styles/
│       └── global.css    # All styling
├── src/
│   ├── components/       # Reusable Astro components
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   ├── Impact.astro
│   │   ├── Mission.astro
│   │   └── Navigation.astro
│   ├── layouts/
│   │   └── BaseLayout.astro
│   └── pages/
│       └── index.astro   # Main page
├── astro.config.mjs
└── package.json
```

## 🧞 Commands

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:4321`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |

## 🎨 Design Philosophy

The design embodies the foundation's name "Bear Hug" through:
- Warm, earthy color palette (gold/bronze accents)
- Protective, enveloping visual elements (gradient orbs)
- Typography that balances elegance (Cormorant Garamond) with clarity (Inter)
- Mysterious yet welcoming atmosphere

## 🚢 Deployment

This site can be deployed to:
- **Netlify** (recommended)
- **Vercel**
- **Cloudflare Pages**
- Any static hosting service

Simply run `npm run build` and deploy the `dist/` folder.

## 🛠️ Customization

- **Content**: Edit components in `src/components/`
- **Colors**: Modify CSS variables in `public/styles/global.css` (`:root` section)
- **Email**: Update contact email in `src/components/Contact.astro`
- **Metadata**: Edit SEO info in `src/layouts/BaseLayout.astro`

## 📦 Built With

- [Astro](https://astro.build) - Static Site Generator
- Vanilla CSS with modern features
- Vanilla JavaScript for interactions

---

Created with care for the Abrazo De Oso Foundation 🐻
