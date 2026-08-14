# Buzón de Marta (nube)

Este repo es el puente entre **Marta** (corriendo en la nube, en una rutina programada de Claude
Code) y la app local de Mario (`/Users/md/Claude/Linkedin feed/`).

- `.claude/agents/redactor-social.md` — el "cerebro" de Marta para la sesión en la nube.
- `marta-inbox.json` — el buzón: Marta añade sus borradores aquí y hace push.

La app de Mario lee este archivo directo desde GitHub (además de su copia local) y los importa solos.
No hace falta tocar nada aquí a mano — Marta lo mantiene actualizado sola, una vez por semana.
