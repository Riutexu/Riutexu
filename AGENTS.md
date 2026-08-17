# AGENTS.md — Riutexu (perfil)

Contrato de trabajo para agentes de IA (opencode, Claude Code, Cursor, Gemini CLI, Copilot...).

Este repositorio es el **perfil de GitHub de Riutexu** y sigue la metodología [superpowers](https://github.com/obra/superpowers) con el ciclo obligatorio:

**Brainstorm → Plan → Build → Test → Review**

Todo agente que toque este repo DEBE completar las 5 fases en orden. Ninguna se salta.

## Fase 1 · Brainstorm
- Carga la skill `brainstorming` antes de proponer cambios.
- Pregunta qué quiere comunicar el perfil: identidad, proyectos, métricas.
- Explora alternativas (estructura, secciones, badges) y valida el diseño con el humano antes de escribir.

## Fase 2 · Plan
- Carga la skill `writing-plans`.
- Descompón el cambio en tareas de 2–5 minutos (ej. sección a editar, badge a añadir, workflow a tocar), cada una con ruta exacta y verificación.

## Fase 3 · Build
- Aplica los cambios por secciones, commits atómicos y mensajes descriptivos.

## Fase 4 · Test
- Verifica que el README renderiza bien (markdown válido), que los badges apuntan a URLs reales y que los workflows de GitHub Actions (`pacman-contribution-graph`, `metrics`) no se rompen.
- No inventes métricas: los badges y stats deben ser dinámicos y reales.

## Fase 5 · Review
- Carga la skill `requesting-code-review`.
- Revisa contra el plan: ¿falta algo? ¿hay datos falsos o desactualizados? ¿el diseño es coherente con la identidad de Riutexu (seguridad, full stack, humor ligero)?

## Contexto del repositorio

- `README.md` — perfil completo (identidad, stack, proyectos, skill tree, roadmap).
- `.github/workflows/main.yml` — regenera el gráfico Pac-Man cada 12 h.
- `.github/workflows/metrics.yml` — regenera `metrics.svg` cada 24 h.
- `metrics.svg` — generado automáticamente; no editar a mano.
- Los repositorios destacados y sus descripciones se gestionan desde el perfil de GitHub, no aquí.
