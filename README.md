# demo-buildsignal

## Problem

Los desarrolladores resuelven errores y descubren aprendizajes durante sus sesiones, pero pierden el contexto y no convierten ese trabajo en contenido.

## How the app works

BuildSignal observa señales de programación, como errores, cambios y pruebas. Detecta problemas resueltos con evidencia y genera un post editable y una imagen PNG para que el usuario los analice, ajuste y publique.

La app no publica automáticamente.

## Notable features

- Detecta problemas, causas y soluciones.
- Explica el aprendizaje encontrado.
- Muestra la evidencia utilizada.
- Genera publicaciones para LinkedIn.
- Genera imágenes PNG de 1080 × 1350.
- Permite editar, copiar, descargar o descartar.
- Sanitiza secretos y datos sensibles antes de procesarlos.
- Compatible con Claude Code y Codex.

## Why did you build this

Para reducir el tiempo entre resolver un problema y convertirlo en contenido.

## Tech stack

TypeScript, Node.js, Next.js, React, Convex, Clerk, Tailwind CSS, Shiki y html-to-image.

## Challenges we ran into

- Detectar aprendizajes sin generar sugerencias irrelevantes.
- Conservar evidencia sin exponer información sensible.
- Convertir sesiones técnicas en historias entendibles.
- Generar imágenes legibles para redes sociales.

## Metrics

- Instalación objetivo: menos de 2 minutos.
- Generación completa: menos de 3 minutos.
- Imagen: 1080 × 1350 px y menos de 2 MB.
- Secretos filtrados: 0.

Abre `index.html` directamente en el navegador. No requiere dependencias.
