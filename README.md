# GEKKINS — TFG Guillermo Álvarez Franganillo · ASIR-2

Este repositorio contiene la documentación y el código fuente del TFG.

## Contenido

```
documentacion_guillermo_alvarez.pdf
source_Gekkins.zip
├── gekkins-front/
├── gekkins-back/
└── gekkins-app/
```

`Gekkins.pdf` — Documentación técnica completa del proyecto.

`gekkins-front/` — Frontend web de la plataforma pública. SPA en React con build propio basado en Bun, desplegada en Cloudflare Pages en `gekkins.com`.

`gekkins-back/` — Backend web de la plataforma pública. API REST en Bun + Hono con autenticación JWT y PostgreSQL, desplegada en servidor Debian vía Cloudflare Tunnel en `api.gekkins.com`.

`gekkins-app/` — Aplicación de escritorio multiplataforma. Gestiona clústeres Docker Swarm de forma visual mediante túneles SSH, built con Electrobun + React.
