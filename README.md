# Next.js + TailwindCSS v4 Boilerplate

Este proyecto es un boilerplate minimalista creado desde cero con Next.js 15 y TailwindCSS v4. Pensado para servir como punto de partida limpio para futuros proyectos.

## 🚀 Tecnologías usadas

- [Next.js 15](https://nextjs.org/)
- [TailwindCSS v4](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)

---

## 🛠️ Instalación paso a paso

### 1. Crear el proyecto

```bash
npx create-next-app@latest my-project-name --typescript


2. Instalar TailwindCSS v4 y dependencias

npm install -D tailwindcss postcss autoprefixer

3. Configurar tailwind.config.js (crearlo manualmente)

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/app/**/*.{js,ts,jsx,tsx}",
    "./src/pages/**/*.{js,ts,jsx,tsx}",
    "./src/components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};

4. Crear postcss.config.js

module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
};

5. Configurar globals.css

@import "tailwindcss/preflight";
@tailwind utilities;

/* Estilos globales opcionales */
body {
  font-family: Arial, Helvetica, sans-serif;
}

6. Importar globals.css en layout.tsx

import "./globals.css";

correr el proyecto:

npm run dev

📁 Estructura limpia

Proyecto sin Navbar ni Footer

Ideal como punto de partida para nuevos proyectos

Listo para producción

📦 Ejecutar en 

git clone https://github.com/tuusuario/nextjs-tailwind-boilerplate.git
cd nextjs-tailwind-boilerplate
npm install
npm run dev

🧠 Nota

Este boilerplate fue creado manualmente sin utilizar npx tailwindcss init ya que en TailwindCSS v4 esta configuración se recomienda hacerla de forma explícita y manual para mayor control.