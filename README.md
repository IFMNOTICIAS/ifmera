# IFMERA Lab AI

Sitio estático de **IFMERA Lab AI** — laboratorio de Inteligencia Artificial del ecosistema IFM Noticias. Diseña y desarrolla CMS de nueva generación y flujos de trabajo con IA para portales de información digital.

- **Dominio:** https://ifmeralabai.com
- **Stack:** [Astro](https://astro.build) + [Tailwind CSS v4](https://tailwindcss.com) (`@tailwindcss/vite`)
- **Fuentes:** Space Grotesk · Inter · JetBrains Mono (self-hosted vía `@fontsource`)
- **Hosting:** Firebase Hosting (CDN global)

## Desarrollo

```bash
npm install
npm run dev        # servidor local en http://localhost:4321
npm run build      # genera /dist
npm run preview    # previsualiza el build
```

## Despliegue

```bash
npm run build
firebase deploy --only hosting
```

## Estructura

```
src/
  layouts/Layout.astro      # <head>, SEO/OG, fuentes, favicon
  styles/global.css         # sistema de diseño (tokens @theme + componentes)
  components/                # Nav, Hero, Manifesto, Services, Product, Case, CTA, Footer, Wordmark
  pages/index.astro          # landing (one-page)
public/
  favicon.svg               # isotipo (tres barras)
```

## Diseño

Dark-first, minimalista. Acento azul tomado del degradado del logo. El isotipo de tres
barras aparece como motivo vivo (la "E" de IFM**E**RA y el ecualizador animado del hero).

---

Independiente del sitio de IFM Noticias.
