# 🎮 GTA-VI Landing Page

Welcome to the **GTA-VI** project – a responsive landing page designed using **Vite + React + TailwindCSS**, and deployed on **GitHub Pages**.

This project serves as a frontend demonstration website for a Grand Theft Auto-themed concept. It is clean, fast, and mobile-friendly.

---

## 🔗 Live Demo

🌐 **[View Live Website](https://youtu.be/TqGdKssP_gI)**

---

## 🛠️ Technologies Used

| Technology       | Purpose                                                         |
| ---------------- | --------------------------------------------------------------- |
| **React.js**     | Handles UI components, page structure, interactivity using JSX. |
| **JavaScript**   | Core logic for components and event handling.                   |
| **HTML**         | Used within React components via JSX for structure and layout.  |
| **TailwindCSS**  | Utility-first CSS framework for modern and responsive styling.  |
| **Vite**         | Fast build tool and development server. Optimized for React.    |
| **GitHub Pages** | Hosts the static site after building it with Vite.              |

---

## 📁 Project Structure

```
GTA-V/
├── public/                # Static assets like icons, images
├── src/
│   ├── components/        # Reusable React components
│   ├── App.jsx            # Root component
│   └── main.jsx           # Entry point, renders App
├── index.html             # Main HTML file used by Vite
├── tailwind.config.js     # TailwindCSS configuration
├── vite.config.js         # Vite configuration (with GitHub Pages base URL)
├── postcss.config.js      # Used to process Tailwind and other PostCSS plugins
├── package.json           # Project dependencies and scripts
└── README.md              # Project documentation
```

---

## 🧪 How Each Technology Contributes

* **React (JSX)**: Manages the dynamic structure of the page using components like `<Navbar />`, `<Hero />`, etc.
* **JavaScript**: Handles event handling (like button clicks), props, and component logic.
* **TailwindCSS**: Applies utility classes directly to HTML elements (in JSX) for styling (e.g., `bg-black`, `text-white`, `flex`, `grid`).
* **HTML (via JSX)**: Structures all the content, images, and sections.
* **Vite**: Bundles the app for development and production, providing fast HMR and optimized builds.
* **GitHub Pages**: Makes the project accessible to anyone via a URL.

---

## 🚀 Deployment

### 1. Install dependencies

```bash
npm install
```

### 2. Build the project

```bash
npm run build
```

### 3. Add `.nojekyll` (optional but recommended)

```bash
echo > dist/.nojekyll
```

### 4. Deploy to GitHub Pages

```bash
npm run deploy
```

Make sure your `package.json` includes:

```json
"homepage": "https://urvil004.github.io/GTA-V",
"scripts": {
  "dev": "vite",
  "build": "vite build",
  "preview": "vite preview",
  "deploy": "gh-pages -d dist"
}
```

Also ensure `vite.config.js` includes:

```js
export default defineConfig({
  base: '/GTA-V/',
  plugins: [react()]
});
```

---

## 📸 Live Demo

> *https://youtu.be/TqGdKssP_gI*

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, raise issues, or submit pull requests.

---

## 📜 License

This project is open-source and free to use for educational and personal purposes.

---

## 👤 Author

**Urvil Darji**
📧 [urvil004@gmail.com](mailto:urvil004@gmail.com)
🔗 [GitHub](https://github.com/urvil004)

---
