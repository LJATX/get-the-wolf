# Get the Wolf — Website

Marketing site for Get the Wolf — the homeowner's remodeling course built by Roy Faust.

## Stack
- **Framework:** Astro
- **Hosting:** Netlify
- **Domain:** getthewolf.info

## Scripts
```
npm install
npm run dev       # start dev server at localhost:4321
npm run build     # build to dist/
npm run preview   # preview production build
```

## Structure
```
src/
  components/   — reusable section components
  data/         — copy, testimonials, FAQ, curriculum
  layouts/      — Base layout
  pages/        — routes (index.astro)
  styles/       — global.css with GTW brand tokens
public/
  assets/
    logos/      — GTW brand logos (SVG)
    roy/        — Roy Faust photography
    imagery/    — editorial + remodel imagery
```
