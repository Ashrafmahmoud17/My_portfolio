# 🌐 Personal Portfolio — AI Engineer & Data Analyst

A modern personal portfolio website built with **React + Vite + TypeScript + Tailwind CSS**, with full Arabic RTL support.

---

## ⚡ Tech Stack

| Technology | Purpose |
|------------|---------|
| React 18 | UI framework |
| TypeScript | Type-safe development |
| Vite | Fast dev server & bundler |
| Tailwind CSS | Styling & layout |
| shadcn/ui | Prebuilt UI components |
| Cairo & Playfair Display | Google Fonts (Arabic + English) |

---

## 🚀 Getting Started

### Prerequisites

- Node.js >= 18
- npm or bun

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/portfolio.git
cd portfolio

# 2. Install dependencies
npm install
# or with bun
bun install

# 3. Set up environment variables
cp .env.example .env

# 4. Start the dev server
npm run dev
```

Open your browser at `http://localhost:5173`

---

## 🏗️ Build for Production

```bash
npm run build
```

Output files will be in the `dist/` folder, ready to deploy.

### Preview the production build

```bash
npm run preview
```

---

## 📁 Project Structure

```
portfolio/
├── public/              # Static assets (images, icons)
├── src/
│   ├── components/      # React components
│   ├── pages/           # Page-level components
│   ├── hooks/           # Custom React hooks
│   ├── lib/             # Utilities and helpers
│   ├── assets/          # Images and static files
│   └── main.tsx         # App entry point
├── .env                 # Environment variables (not committed)
├── index.html           # HTML template
├── tailwind.config.ts   # Tailwind configuration
├── vite.config.ts       # Vite configuration
└── tsconfig.json        # TypeScript configuration
```

---

## 🌍 Deployment

### Vercel (recommended)

```bash
npm i -g vercel
vercel
```

### Netlify

Drag and drop the `dist/` folder at [netlify.com/drop](https://netlify.com/drop)

### GitHub Pages

```bash
npm run build
# Push the contents of dist/ to the gh-pages branch
```

---

## ⚙️ Environment Variables

Create a `.env` file in the project root:

```env
VITE_APP_TITLE=My Portfolio
VITE_CONTACT_EMAIL=@email.com
```




## 🎨 Customization

- **Colors** — edit `tailwind.config.ts`
- **Fonts** — update the `<link>` tags in `index.html`
- **Content** — edit the component files inside `src/components/`
- **RTL/LTR** — toggle the `dir` attribute in `index.html`

---

## 📜 License

This project is open source under the [MIT License](LICENSE).
