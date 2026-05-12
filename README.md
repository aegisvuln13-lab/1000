# SaaS Factory — Setup Prompt

Instala todo tu entorno de desarrollo con IA en un solo prompt. Cero experiencia necesaria.

## ¿Cómo usarlo?

1. Abre **Anthropic Claude**, **Cursor**, **Windsurf**, o cualquier agente de IA con acceso a terminal.
2. Copia el contenido de [`prompt.txt`](./prompt.txt).
3. Pégalo en el chat del agente y pulsa Enter.
4. Deja que la IA guíe todo el proceso.

## ¿Qué hace el prompt?

El agente sigue tres fases:

| Fase | Descripción |
|------|-------------|
| **Fase 1 — Investigación** | Lee tu sistema sin tocar nada: SO, versión, herramientas ya instaladas, espacio en disco y permisos. |
| **Fase 2 — Plan** | Propone exactamente qué instalar y espera tu aprobación antes de hacer nada. |
| **Fase 3 — Instalación** | Instala y verifica, paso a paso: Git, Node.js, Python y Claude Code. |

## Herramientas que instala

- **Git** — Control de versiones
- **Node.js** — Motor para aplicaciones web (vía nvm)
- **Python** — Automatización e IA
- **Claude Code** — Agente de IA para programar (`npm install -g @anthropic-ai/claude-code`)

Compatible con **Mac**, **Windows** (con o sin WSL2) y **Linux**.

## Requisitos previos

- Al menos **5 GB** de espacio libre en disco.
- Conexión a internet.
- Cuenta en [claude.ai](https://claude.ai) con plan Pro ($20/mes) o Max ($100/mes) para usar Claude Code.

---

## Plan de negocio — 180 días hacia 50.000 USD

El archivo [`plan-180-dias.md`](./plan-180-dias.md) recoge los 5 nichos de servicios productizados con automatización local que mejor encajan con esta infraestructura, junto con estimaciones realistas de ingresos y las herramientas de software recomendadas para cada uno.

