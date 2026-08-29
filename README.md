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

## Business metrics

- **Proyectos activados:** cantidad de proyectos que empiezan a registrar sesiones.
- **Momentos detectados:** cantidad de aprendizajes encontrados.
- **Tasa de aceptación:** sugerencias aceptadas / momentos detectados.
- **Tasa de publicación:** publicaciones realizadas / sugerencias aceptadas.
- **Publicaciones por usuario:** frecuencia con que el contenido sale del proyecto.
- **Retención:** usuarios que vuelven a usar BuildSignal después de 7 y 30 días.
- **Conversión a pago:** cuentas de pago / cuentas activas.
- **Ingresos mensuales:** suscripciones + planes para equipos.

## Cómo beneficia al negocio

BuildSignal puede generar ingresos con un plan gratuito limitado, un plan Pro para publicaciones y proyectos adicionales, y un plan para equipos con métricas compartidas y controles de privacidad. El valor comercial se mide por la cantidad de proyectos activados, sugerencias aceptadas, publicaciones realizadas y usuarios que permanecen activos.

Abre `index.html` directamente en el navegador. No requiere dependencias.
