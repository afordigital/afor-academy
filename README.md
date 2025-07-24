<div align="center">

# Afor-Academy - Plataforma de Aprendizaje Web Neo-Brutalista

![GitHub stars](https://img.shields.io/github/stars/afordigital/afor-academy?style=social) ![GitHub forks](https://img.shields.io/github/forks/afordigital/afor-academy?style=social) ![GitHub issues](https://img.shields.io/github/issues/afordigital/afor-academy) ![Contributors](https://img.shields.io/github/contributors/afordigital/afor-academy)

**Afor-Academy** es una plataforma web con un diseño neo-brutalista, dedicada a la enseñanza de diseño y desarrollo web a otro nivel.

[Reportar Bug](https://github.com/afordigital/afor-academy/issues)

</div>

## 📸 Vista Previa

<!-- Cuando el archivo cover.jpg esté en el repositorio, esta imagen se mostrará -->

![Afor Academy Preview](./cover.jpg)

## 🚀 Acerca de Afor-Academy

Afor-Academy es una plataforma de aprendizaje enfocada en tecnologías web modernas, con una estética neo-brutalista que busca romper con los diseños tradicionales. Nuestro objetivo es ofrecer contenido de alta calidad de una manera visualmente impactante y directa.

### ✨ Características Principales

- **🎨 Diseño Neo-Brutalista**: Una interfaz única, con tipografías fuertes, colores vibrantes y sin miedo a mostrar la estructura.
- **📚 Cursos Interactivos**: Contenido educativo sobre diseño y desarrollo web (¡Próximamente!).
- **🤖 Animaciones SVG**: Uso de animaciones para una experiencia más dinámica.
- **⚡ Performance**: Construido con Astro para un rendimiento óptimo y carga rápida.

## 📊 Arquitectura del Proyecto

```mermaid
graph TD
    subgraph "Usuario Final"
        A[Visitante]
    end

    subgraph "Build & Despliegue (Astro)"
        C(Afor Academy - Código Fuente)
        C --> D["Páginas y Rutas<br/>/src/pages"]
        C --> E["Layouts<br/>/src/layouts"]
        C --> F["Componentes<br/>/src/components"]
        C --> G["Contenido (Cursos)<br/>/src/content"]
        C --> H["Assets Estáticos<br/>/public"]
    end

    subgraph "Producción (Hosting)"
        B["Sitio Web Estático<br/>HTML, CSS, JS"]
    end

    A --> B
    C -- Proceso de Build --> B

    D -- Utiliza --> E
    D -- Utiliza --> F
    F -- Puede contener --> F
    D -- Renderiza --> G

    style A fill:#a488ef,stroke:#333,stroke-width:2px,color:#fff
    style B fill:#89dceb,stroke:#333,stroke-width:2px,color:#1e1e2e
    style C fill:#ff7a5c,stroke:#333,stroke-width:2px,color:#fff
    style D fill:#fab387,stroke:#333,stroke-width:2px,color:#1e1e2e
    style E fill:#fab387,stroke:#333,stroke-width:2px,color:#1e1e2e
    style F fill:#fab387,stroke:#333,stroke-width:2px,color:#1e1e2e
    style G fill:#fab387,stroke:#333,stroke-width:2px,color:#1e1e2e
    style H fill:#fab387,stroke:#333,stroke-width:2px,color:#1e1e2e
```

## 📚 Tabla de Contenidos

- [Afor-Academy - Plataforma de Aprendizaje Web Neo-Brutalista](#afor-academy---plataforma-de-aprendizaje-web-neo-brutalista)
  - [📸 Vista Previa](#-vista-previa)
  - [🚀 Acerca de Afor-Academy](#-acerca-de-afor-academy)
    - [✨ Características Principales](#-características-principales)
  - [📊 Arquitectura del Sistema (En Desarrollo)](#-arquitectura-del-sistema-en-desarrollo)
  - [📚 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🚀 Comenzar](#-comenzar)
    - [📋 Prerrequisitos](#-prerrequisitos)
    - [⚡ Instalación Rápida](#-instalación-rápida)
    - [📦 Construir para Producción](#-construir-para-producción)
    - [🔍 Vista Previa de Producción](#-vista-previa-de-producción)
  - [🤝 Contribuir](#-contribuir)
  - [👥 Autores](#-autores)
  - [🛠️ Stack Tecnológico](#️-stack-tecnológico)

## 🚀 Comenzar

### 📋 Prerrequisitos

Asegúrate de tener instalado:

- **Node.js** (versión 18 o superior)
- **pnpm** (versión 10 o superior)

### ⚡ Instalación Rápida

1. **Clona o haz fork del repositorio**

   ```bash
   git clone https://github.com/afordigital/afor-academy.git
   cd afor-academy
   ```

2. **Instala las dependencias**

   ```bash
   pnpm install
   ```

3. **Ejecuta el proyecto**

   ```bash
   pnpm dev
   ```

4. **Abre tu navegador y visita**

   [http://localhost:4321](http://localhost:4321)

### 📦 Construir para Producción

Para crear una compilación lista para producción:

```bash
pnpm build
```

### 🔍 Vista Previa de Producción

Para previsualizar la compilación de producción localmente:

```bash
 pnpm preview
```

## 🤝 Contribuir

Si quieres contribuir a este proyecto, puedes hacerlo leyendo nuestra [Guía de Contribución](./CONTRIBUTING.md).

---

## 👥 Autores

<a href="https://github.com/afordigital">
   <img width="50px" src="https://avatars.githubusercontent.com/u/43246362?v=4" />
</a>

**¡Gracias a todos los colaboradores que han hecho posible este proyecto!**

[![Contributors](https://contrib.rocks/image?repo=afordigital/afor-academy)](https://github.com/afordigital/afor-academy/graphs/contributors)

## 🛠️ Stack Tecnológico

![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

### 🔧 Tecnologías Principales

- **Framework**: Astro
- **Styling**: TailwindCSS
- **Build Tool**: Vite

---

Hecho con ❤️ por [comuafor 🐀](https://discord.com/invite/comuafor)
