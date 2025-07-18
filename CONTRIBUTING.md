# Contribuir a Afor-Academy

¡Gracias por tu interés en contribuir! Para asegurar una colaboración fluida y eficiente, por favor sigue estas pautas.

## Tabla de Contenidos

- [Cómo contribuir](#-cómo-contribuir)
- [Código de Conducta](#-código-de-conducta)
- [Cómo Reportar Problemas](#-cómo-reportar-problemas)
- [Cómo Proponer Nuevas Características](#-cómo-proponer-nuevas-características)
- [Cómo Hacer Fork](#-cómo-hacer-fork)
- [Cómo Enviar un Pull Request](#-cómo-enviar-un-pull-request)
- [Antes de Enviar un Pull Request](#-antes-de-enviar-un-pull-request)
- [Envío de Issues](#-envío-de-issues)

## 🤝 Cómo contribuir

¡Gracias por tu interés en contribuir! Para asegurar una colaboración fluida y eficiente, por favor sigue estas pautas.

1. **Explora el Proyecto**: Revisa el [README](./README.md), la estructura y el código para entender el proyecto.
2. **Revisa Issues Abiertos**: Visita la [sección de Issues](https://github.com/afordigital/brand-generator/issues) para ver cómo puedes ayudar, o abre un nuevo issue para sugerir una característica o reportar un bug.
3. **Fork y clona**: Haz un fork del repositorio y clónalo en tu máquina local.

## 📋 Código de Conducta

Estamos comprometidos a mantener un ambiente de colaboración respetuoso y acogedor.

### Nuestros Estándares

- Usar un lenguaje acogedor e inclusivo
- Ser respetuoso con los diferentes puntos de vista y experiencias
- Aceptar críticas constructivas con gracia
- Enfocarse en lo que es mejor para la comunidad
- Mostrar empatía hacia otros miembros de la comunidad

## 🐛 Cómo Reportar Problemas

Si encuentras un bug o problema:

1. **Busca Issues Existentes**: Verifica si el problema ya ha sido reportado.
2. **Abre un Nuevo Issue**: Si es un problema nuevo, abre uno en la [sección de Issues](https://github.com/afordigital/brand-generator/issues) con una descripción clara y concisa.

### Información a Incluir

- **Descripción del problema**: Explica qué esperabas que pasara vs. qué realmente pasó
- **Pasos para reproducir**: Lista los pasos específicos para recrear el problema
- **Entorno**: Versión del navegador, sistema operativo, etc.
- **Screenshots**: Si es aplicable, agrega capturas de pantalla

## 💡 Cómo Proponer Nuevas Características

Para proponer una nueva característica:

1. **Abre un Issue**: Antes de comenzar a trabajar, abre un nuevo issue en la [sección de Issues](https://github.com/afordigital/brand-generator/issues).
2. **Obtén Feedback**: Espera retroalimentación y sugerencias de colaboradores o mantenedores antes de proceder.
3. **Diseña la Solución**: Describe cómo planeas implementar la característica.

## 🍴 Cómo Hacer Fork

Para contribuir a Afor-Academy, primero necesitas hacer fork del repositorio:

1. **Ve al Repositorio en GitHub**: Visita [Afor-Academy](https://github.com/afordigital/afor-academy).
2. **Haz Click en Fork**: En la esquina superior derecha de la página del repositorio, haz click en el botón **Fork**. Esto crea una copia del repositorio en tu cuenta de GitHub.
3. **Clona tu Fork**: Abre una terminal en tu máquina local y ejecuta el siguiente comando para clonar tu fork:

```bash
git clone https://github.com/TU_USUARIO/afor-academy.git
cd afor-academy
```

4. **Instala las Dependencias**: Instala las dependencias del proyecto:

```bash
pnpm install
```

5. **Ejecuta el Proyecto**: Inicia el servidor de desarrollo:

```bash
pnpm dev
```

## 🔄 Cómo Enviar un Pull Request

Para enviar un pull request (PR):

1. **Sincroniza tu Repositorio**: Asegúrate de que tu rama esté actualizada con la rama main del repositorio original.
2. **Crea una Nueva Rama**: Haz tus cambios en una rama separada y commitéalos con mensajes claros.
3. **Prueba tus Cambios**: Asegúrate de que tus cambios no introduzcan errores y que todo funcione como se espera.
4. **Abre el Pull Request**: Envía un PR desde tu rama a la rama main del repositorio, incluyendo una descripción detallada de tus cambios.
5. **Espera la Revisión**: Los mantenedores revisarán tu PR y proporcionarán retroalimentación. Haz las modificaciones necesarias.

### Estándares de Código

- **Sigue las convenciones**: Usa las mismas convenciones de código que el resto del proyecto
- **Linting**: Ejecuta `pnpm lint` antes de hacer commit
- **Formato**: Ejecuta `pnpm format:fix` para formatear tu código
- **Testing**: Si agregas nueva funcionalidad, considera agregar tests
- **Commits descriptivos**: Usa mensajes de commit claros y descriptivos

## ⚡ Antes de enviar un Pull Request

Para evitar conflictos y asegurar que tu fork esté actualizado con el repositorio original, **sigue estos pasos cuidadosamente:**

### 1. Guarda Cambios Locales (Opcional)

Si tienes cambios sin commitear y no quieres perderlos:

```bash
git stash
```

### 2. Agrega el Repositorio Original como upstream (Solo Una Vez)

Si aún no has agregado el repo original como remoto:

```bash
git remote add upstream https://github.com/afordigital/brand-generator.git
```

### 3. Cambia a tu Rama main

Asegúrate de estar en la rama main de tu fork:

```bash
git checkout main
```

### 4. Sincroniza con el Repo Original (upstream)

Obtén los últimos cambios del repositorio original:

```bash
git fetch upstream
git rebase upstream/main
```

### 5. Actualiza la Rama Main en tu Fork

Actualiza tu repositorio forkeado en GitHub:

```bash
git push origin main
```

### 6. Cambia a tu Rama de Característica/PR

Reemplaza `tu-rama` con el nombre de tu rama de trabajo:

```bash
git checkout tu-rama
```

### 7. Rebasa tu Rama sobre la main Actualizada

Esto ayuda a evitar conflictos de merge en tu PR:

```bash
git rebase main
```

### 8. (Opcional) Restaura tus Cambios Guardados

Si guardaste cambios anteriormente:

```bash
git stash pop
```

### 9. Sube tu Rama

Sube tu rama rebasada a tu repositorio forkeado:

```bash
git push origin tu-rama
```

Si rebasaste y ya habías subido antes, podrías necesitar force push:

```bash
git push origin tu-rama --force
```

### 10. Comparar y Pull Request

Ve a tu fork en GitHub, y deberías ver un botón "Compare & pull request".
Haz click en él, agrega un título claro y descripción para tu PR, luego envíalo.

## 📝 Envío de Issues

Para asegurar que tu issue sea manejado eficientemente:

1. **Proporciona Información Detallada**: Incluye detalles relevantes sobre el bug o solicitud de característica. Esto puede incluir pasos para reproducir el problema, screenshots o ejemplos de código.
2. **Usa Etiquetas Apropiadas**: Si es posible, usa las etiquetas proporcionadas para categorizar tu issue (como bug, enhancement, etc.).
3. **Sé Claro y Conciso**: Escribe una descripción clara y al punto para que los mantenedores puedan entender rápidamente el problema o solicitud.
4. **Revisa Issues Existentes**: Antes de abrir un nuevo issue, revisa los existentes para asegurar que el mismo problema o solicitud no haya sido ya reportado.

### Tipos de Issues

- **🐛 Bug Report**: Para reportar errores o comportamientos inesperados
- **💡 Feature Request**: Para sugerir nuevas características o mejoras
- **📚 Documentation**: Para mejoras en la documentación
- **🎨 UI/UX**: Para mejoras en la interfaz de usuario o experiencia de usuario
- **⚡ Performance**: Para optimizaciones de rendimiento

## 🚀 Áreas donde Puedes Contribuir

### Frontend (React + TypeScript)

- Mejoras en la interfaz de usuario de Hambot
- Nuevos componentes de vista previa para paletas
- Optimizaciones de rendimiento
- Mejoras en la experiencia de usuario del chat

### Integración de IA

- Mejoras en los prompts para generar mejores paletas
- Nuevas funcionalidades de generación de marca
- Optimización de respuestas del chatbot

### Documentación

- Mejoras en el README
- Documentación de componentes
- Guías de usuario
- Tutoriales y ejemplos

### Testing

- Tests unitarios para componentes
- Tests de integración
- Tests end-to-end

---

¡Gracias por tu interés y contribución a Hambot Brand Generator! ¡Tu ayuda es muy valiosa! 🎨

Para cualquier pregunta, no dudes en unirte a nuestra comunidad en [Discord](https://discord.com/invite/comuafor) 🐀
