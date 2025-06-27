
# Nudger List Frontend

This is the frontend application for the Nudger List project, built with:

- **Vue.js 3.4** — JavaScript Framework  
- **Pinia 2.1** — State Management  
- **Vite 6.3** — Build Tool and Development Server  
- **TailwindCSS 4.0** — Utility-first CSS Framework

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or above  
- [npm](https://www.npmjs.com/) (comes with Node.js)

---

### Installation

1. Clone the repository:

```
git clone <your-repo-url>
cd nudger-list-front
```

2. Install dependencies:

```
npm install
```

---

### Running Locally

Start the development server with:

```
npm run dev
```

Open your browser and navigate to `http://localhost:5173`

You should see the app running with TailwindCSS styles applied.

---

### Building for Production

To build the optimized production files, run:

```
npm run build
```

The build output will be in the `dist/` folder.

---

### Preview Production Build

You can locally preview the production build with:

```
npm run preview
```

---

## 📂 Project Structure

```
nudger-list-front/
├── src/
│   ├── assets/
│   │   └── main.css       # TailwindCSS entrypoint
│   ├── components/        # Vue components
│   ├── App.vue            # Root Vue component
│   └── main.js            # Application bootstrap
├── index.html             # HTML template
├── package.json           # Project dependencies and scripts
├── tailwind.config.js     # TailwindCSS configuration
├── postcss.config.js      # PostCSS configuration
└── vite.config.js         # Vite configuration
```

---

## 🧪 Testing

(If tests are added later)

---

## ⚙️ Configuration

Make sure `tailwind.config.js` includes your source files in the `content` array to enable TailwindCSS purging and JIT:

```js
export default {
  content: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}"
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

---

## 📖 Useful Commands

| Command           | Description                    |
|-------------------|-------------------------------|
| `npm run dev`     | Run development server         |
| `npm run build`   | Build for production           |
| `npm run preview` | Preview production build locally |

---

## 📦 Dependencies

- Vue 3.4  
- Pinia 2.1  
- Vite 6.3  
- TailwindCSS 4.0  
- PostCSS 8+  
- Autoprefixer 10+

---

## License

MIT © Your Name

---

*Feel free to reach out if you have questions or need support.*
