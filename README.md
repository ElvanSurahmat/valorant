# Awwwards Website

A modern, responsive website built with [React](https://react.dev/) and [Vite](https://vitejs.dev/), styled using [Tailwind CSS](https://tailwindcss.com/).  
This project features custom fonts, animated UI, and a modular component structure.

## Features

- ⚡️ Fast development with Vite
- 🎨 Utility-first styling with Tailwind CSS
- 🖼️ Custom fonts and assets
- 🧩 Modular React components
- ✨ Animations with GSAP

## Project Structure

```
valo/
├── public/           # Static assets (fonts, images, audio, videos)
├── src/
│   ├── assets/       # Source assets (if any)
│   ├── components/   # React components
│   ├── App.jsx       # Main app component
│   ├── index.css     # Global styles and Tailwind imports
│   └── main.jsx      # Entry point
├── index.html        # HTML template
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
├── package.json
└── ...
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

### Development

Start the local development server:

```sh
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

### Build

To build for production:

```sh
npm run build
```

Preview the production build:

```sh
npm run preview
```

### Lint

To lint the codebase:

```sh
npm run lint
```

## Customization

- **Fonts:** Add or replace font files in `public/fonts/` and update `src/index.css` and `tailwind.config.js` as needed.
- **Assets:** Place images, audio, and videos in the respective folders under `public/`.

## License

[MIT](LICENSE) © Elvan Surahmat

---
