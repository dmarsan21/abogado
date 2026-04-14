<div align="center">
  <h1 align="center">⚖️ Martínez & Asociados - Legal Tech Landing Page</h1>
  <p align="center">
    <strong>Una landing page ultra-moderna para servicios legales, construida con Astro y Tailwind CSS, diseñada para transmitir confianza y tecnología.</strong>
  </p>
  <p align="center">
    <a href="https://astro.build"><img src="https://img.shields.io/badge/Astro-0C1424?style=for-the-badge&logo=astro&logoColor=white" alt="Astro" /></a>
    <a href="https://tailwindcss.com"><img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" /></a>
    <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" /></a>
  </p>
</div>

<br />

Una presencia digital de vanguardia para la firma **Martínez & Asociados**, enfocada en destacar su visión "Legal Tech". Diseñada con un enfoque futurista y profesional, implementando una paleta de colores oscuros con acentos en cyan (Dark Mode Aesthetic), tipografía Sans-Serif minimalista y efectos visuales avanzados como *glassmorphism* y transiciones suaves para una experiencia de usuario inigualable.

## ✨ Características Principales

- ⚖️ **Estética Legal Tech**: Interfaz sofisticada orientada a la abogacía moderna y consultoría tecnológica.
- 📱 **Mobile-First & Responsivo**: Adaptabilidad completa para garantizar un uso confortable desde dispositivos móviles hasta resoluciones ultra-anchas.
- 🎨 **Componentes Modernos**: Uso intensivo de *glassmorphism*, bordes sutiles y efectos de iluminación que resaltan el profesionalismo de los servicios, el equipo y la firma.
- ⚡ **Performance Absoluta**: Arquitectura basada en generación estática (SSG) gracias a Astro, resultando en velocidad de carga instantánea y puntaje SEO excepcional.
- 🌗 **Diseño Profundo y Fluido**: Uso de tonos oscuros elegantes, acentos *cyan* de alto contraste y animaciones sutiles interactivas (hover states).

## 🛠️ Tecnologías Utilizadas

- **Framework Principal**: [Astro v6](https://astro.build/) - Para la generación de renderizado ultra-rápido sin cargar la página de JavaScript innecesario.
- **Estilos**: [Tailwind CSS v4](https://tailwindcss.com/) - Implementado vía Vite para diseño escalable, limpio e impulsado por clases utilitarias.
- **Lenguaje**: TypeScript - Permitiendo tipado fuerte de componentes y configuración estricta para una excelente experiencia del desarrollador (DX).

## 🚀 Instalación y Desarrollo Local

Puedes hacer checkout del proyecto en tu máquina y lanzar el entorno de desarrollo en minutos:

1. **Clona el repositorio** en tu ordenador:
   ```bash
   git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git
   cd abogados
   ```

2. **Instala las dependencias necesarias** empleando tu gestor preferido (ha sido configurado en base a `pnpm`):
   ```bash
   pnpm install
   # Alternativas si no usas pnpm:
   # npm install o yarn install
   ```

3. **Inicia el servidor local de desarrollo**:
   ```bash
   pnpm run dev
   ```

4. **Visualiza el proyecto**: Visita `http://localhost:4321` en tu navegador de preferencia. Tus cambios se actualizarán instantáneamente.

## 📦 Scripts de Utilidad

Comandos básicos que puedes usar dentro del directorio raíz desde la línea de comandos (terminal):

| Comando | Descripción |
| :--- | :--- |
| `pnpm run dev` | Inicia el servidor de desarrollo en `localhost:4321`. |
| `pnpm run build` | Construye los archivos finales minimizados de producción (en `./dist/`). |
| `pnpm run preview` | Despliega localmente el contenido de `./dist/` para previsualizar antes de publicar. |
| `pnpm astro [comando]`| Ejecuta tareas propias y administrativas dentro del CLI de Astro. |

## 📁 Estructura del Archivo

Organización simplificada de los elementos primarios del catálogo del proyecto:

```text
/
├── public/                 # Archivos estáticos inyectables directos (Favicons) sin ser procesados
├── src/
│   ├── components/         # Bloques modulares de la Interfaz (Navbar, Hero, Services, Features, Contact, Footer)
│   ├── layouts/            # Plantillas maestras que proveen la estructura principal de las páginas
│   ├── pages/              # Mapeo de rutas automáticas (index.astro generará '/')
│   └── styles/             # Hojas de estilo globales inyectando la configuración de Tailwind
├── astro.config.mjs        # Opciones y configuración empaquetada de Astro
├── package.json            # Metadatos del repositorio y mapeos de dependencias
└── tsconfig.json           # Configuración sobre las métricas de chequeo de TypeScript
```

## 🌐 Guía de Despliegue (Deploy)

Dado que este proyecto es estático, los tiempos de carga en la web son increíblemente veloces; optimizado para lanzarse de inmediato.

**Métodos de lanzamiento sugeridos:**
- **Vercel** o **Netlify**: Simplemente vincula tu repositorio remoto en la plataforma e iniciará el ciclo de build automáticamente con cada *push*.
- **GitHub Pages**: Perfectamente compatible usando GitHub Actions. Puedes consultar el paso a paso en la [Guía Oficial de Despliegue de Astro para GitHub](https://docs.astro.build/es/guides/deploy/github/).

---

<p align="center">
  Construido con <a href="https://astro.build">Astro</a> 🚀 - Transmitiendo Autoridad y Vanguardia Legal en cada línea de código.
</p>
