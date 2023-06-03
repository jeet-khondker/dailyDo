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

## Deletion of the default HTML Code from `src/App.tsx` and replace it with empty `<section></section>` Tag

1. Change 👇

```html
<div className="App">
  <header className="App-header">
    <img src={logo} className="App-logo" alt="logo" />
    <p>
      Edit <code>src/App.tsx</code> and save to reload.
    </p>
    <a
      className="App-link"
      href="https://reactjs.org"
      target="_blank"
      rel="noopener noreferrer"
    >
      Learn React
    </a>
  </header>
</div>
```

to 👇

```html
<section></section>
```