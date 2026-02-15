# 🚀 Ultra-Fast Vue Portfolio Template

A high-performance, visually stunning, and meticulously engineered portfolio template designed for developers who prioritize speed, stability, and modern aesthetics.

![Lighthouse Score](https://img.shields.io/badge/Lighthouse-100-brightgreen?style=for-the-badge&logo=lighthouse)
![CLS Score](https://img.shields.io/badge/CLS-0.04s-blue?style=for-the-badge)

## ✨ Key Features

- **💯 Perfect Performance Score:** Optimized out-of-the-box to hit a 100 Performance Score on Google Lighthouse.
- **🏗️ Ultra-Stable Layout (CLS):** Maintains a Cumulative Layout Shift of **0.04s**, ensuring perfect visual stability even with heavy assets.
- **📧 EmailJS Integration:** Fully functional contact form integration—just plug in your API keys.
- **📱 Responsive & Atomic UI:** Styled with **UnoCSS** for near-zero CSS overhead and rapid development.
- **🌊 Fluid UX:** Featuring **Lenis** for premium smooth scrolling and **Lucide** for crisp, scalable iconography.
- **🎨 Interactive Elements:** Modern UI components sourced from **Uiverse.io**, optimized for performance.
- **🔍 SEO-Ready:** Clean semantic structure with placeholders for your custom metadata.

## 🛠️ Tech Stack

- **Framework:** [Vue.js 3](https://vuejs.org/) (Composition API)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [UnoCSS](https://unocss.dev/) (Instant Atomic CSS)
- **Icons:** [Lucide Vue Next](https://lucide.dev/)
- **Smooth Scroll:** [Lenis](https://lenis.darkroom.engineering/)
- **Form Handling:** [EmailJS](https://www.emailjs.com/)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Revan5679/template-portfolio.git
cd your-repo-name
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Development Server

```bash
npm run dev
```

## ⚙️ Configuration (CRITICAL)

### EmailJS Setup

To enable the contact form, you must configure your environment variables:

1. Copy `.env.example` to a new file named `.env`.
2. Replace the placeholders with your actual **EmailJS** credentials:
   - `VITE_EMAILJS_SERVICE_ID`
   - `VITE_EMAILJS_TEMPLATE_ID`
   - `VITE_EMAILJS_PUBLIC_KEY`

### Maintaining Performance

To keep the **0.04s CLS score**, always ensure that any new images added to the project have defined `width` and `height` attributes on the `<img>` tags. This allows the browser to allocate space before the image loads, preventing layout jumps.

## 📦 Deployment

This template is optimized for zero-config deployment on modern platforms:

### Vercel / Netlify

1. Push your code to GitHub.
2. Import the project into Vercel or Netlify.
3. **Important:** Add your `.env` variables in the platform's Dashboard under "Environment Variables".
4. Build Command: `npm run build`
5. Output Directory: `dist`

---

Built with precision for the modern web.
