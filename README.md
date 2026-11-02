# bang-ignore

En un `.gitignore`, una línea que empieza con `!` (el "bang") hace lo contrario de ignorar: `!archivo` significa "este sí se incluye", aunque todo lo demás se ignore.

Este repo es eso. Mis proyectos más interesantes tienen código privado (datos personales o de clientes), así que mis `.gitignore` los dejan afuera. Acá va lo que sí se puede mostrar: el problema, las decisiones técnicas, el stack y una demo con datos inventados.

## Proyectos

| Proyecto | Qué es | Stack |
|---|---|---|
| [Calis Trainer](proyectos/calis-trainer/) | Web y panel de administración para una entrenadora de calistenia, con investigación de marca previa (trabajo freelance entregado) | Astro, TypeScript, Sanity, Vercel |
| [Polar Canvas](proyectos/polar-canvas/) | Sitio de portfolio bilingüe para una ilustradora, con panel de administración propio (trabajo freelance entregado) | Astro, TypeScript, React, Cloudflare R2, Vercel |
| [Postulaciones](proyectos/postulaciones/) | Herramienta local que adapta mi CV a cada oferta de trabajo y devuelve un CV en Word, una carta y un análisis (y, si se elige, posibles preguntas de entrevista) | Node.js, Claude Code, docx |
| [Rumbo España](proyectos/rumbo-espana/) | Sistema web local para organizar la información para vivir en España, con investigación mensual hecha por una IA | Node.js, Express, JSON, Claude Code |

## Cómo está organizado

Cada carpeta de `proyectos/` tiene un `README.md` con la misma estructura (ver [la plantilla](plantilla/README.plantilla.md)) y una carpeta `media/` con capturas y GIFs.
