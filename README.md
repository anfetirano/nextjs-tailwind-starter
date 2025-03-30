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



instrucciones para el uso y clonar

# Documentación: Preparación del Proyecto "nextjs-fetching-practice" a partir de un Boilerplate

## 📁 Paso 1: Clonar el boilerplate desde GitHub

El proyecto base fue clonado desde un repositorio previamente creado con una instalación profesional de Next.js y TailwindCSS v4. El repositorio original fue:

```
https://github.com/anfetirano/nextjs-tailwind-starter.git
```

Comando utilizado para clonar:
```bash
cd D:/Programacion
git clone https://github.com/anfetirano/nextjs-tailwind-starter.git
```

Esto generó una carpeta llamada:
```
nextjs-tailwind-starter
```

---

## ✏️ Paso 2: Renombrar el proyecto localmente

Para crear un nuevo proyecto a partir del boilerplate y diferenciarlo, se renombró la carpeta a:
```
nextjs-fetching-practice
```

Esto puede hacerse manualmente desde el explorador de archivos o con:
```bash
mv nextjs-tailwind-starter nextjs-fetching-practice
```

---

## 🛋️ Paso 3: Inicializar un nuevo repositorio Git

Una vez renombrado, se inicializó el proyecto como un nuevo repositorio Git para no conservar el historial del boilerplate anterior:

```bash
cd nextjs-fetching-practice
rm -rf .git
git init
```

---

## 🌐 Paso 4: Crear un nuevo repositorio en GitHub

Desde GitHub se creó un nuevo repositorio:
```
https://github.com/anfetirano/nextjs-fetching-practice.git
```

Y se vinculó al repositorio local con:
```bash
git remote add origin https://github.com/anfetirano/nextjs-fetching-practice.git
```

---

## 📂 Paso 5: Primer commit y push

Se agregaron los archivos y se subió el primer commit:

```bash
git add .
git commit -m "Initial commit from boilerplate"
git push -u origin master
```

---

## 🖊️ Resultado Final

Ya tienes un nuevo proyecto listo en local y sincronizado con GitHub, completamente funcional y basado en una estructura profesional con TailwindCSS v4.

Repositorio final:
```
https://github.com/anfetirano/nextjs-fetching-practice
```


IMPORTANTE AL FINAL DE TODO ME QUEDARON VARIOS ERRORES EN EL LAYOUT Y EL PAGE LA SOLUCION ES 

npm install 
