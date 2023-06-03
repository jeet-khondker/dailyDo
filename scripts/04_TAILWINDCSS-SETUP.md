## Navigation to `frontend` Directory

## Installation of TailWind CSS

```bash
yarn add -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

## Recreation of TailWind CSS Configuration File `tailwind.config.js`

```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  node: "jit",
  content: [
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

## Addition of TailWind CSS Directives to CSS File `src/App.css`

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Deletion of the `styles` object from `pages/index.tsx` (mainly the whole `class` attribute like below:

1. Change 👇

```html
<div className="{ styles.container }"ren></div>
```

to 👇

```html
<section></section>
```

2. Remove `<main></main>` tag block and `<footer></footer>` tag block

```html
<main></main>
<footer></footer>
```