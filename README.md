# Fichas técnicas PDF · Antares Nova

Skill reutilizable en español para encontrar fichas técnicas originales de producto o, si no existen, crear una ficha corporativa de Antares Nova. Incluye tres logos SVG transparentes y reglas para documentos de varias páginas. No contiene datos de clientes, fichas de ejemplo, proveedores, credenciales ni scripts que ejecutar.

## Instalación

Copia la carpeta completa [`skills/fichas-tecnicas-pdf`](skills/fichas-tecnicas-pdf/) en la carpeta de habilidades de tu agente. Conserva `SKILL.md`, `assets/` y `references/` juntos.

| Agente | Carpeta del proyecto |
| --- | --- |
| Codex | `.agents/skills/fichas-tecnicas-pdf/` |
| Claude Code | `.claude/skills/fichas-tecnicas-pdf/` |

En **Claude web**, comprime únicamente la carpeta `fichas-tecnicas-pdf` conservándola como raíz del ZIP. Luego abre **Customize → Skills → + → Create skill → Upload a skill**. Requiere que las skills y la ejecución de código estén habilitadas.

Para otra IA, usa su importador si admite Agent Skills. Si no, copia el contenido de [SKILL.md](skills/fichas-tecnicas-pdf/SKILL.md) a las instrucciones de un chat o proyecto y adjunta los tres logos.

**Ejemplo:** «Usa la skill Fichas técnicas PDF para este equipo. Si ya existe la ficha original del modelo exacto, entrégala completa sin modificar».

Documentación: [OpenAI: instalación de skills](https://developers.openai.com/api/reference/cli) · [Claude: uso de skills](https://support.claude.com/en/articles/12512180-use-skills-in-claude).
