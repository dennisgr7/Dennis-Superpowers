# AGENTS.md

Este archivo sigue la convención [AGENTS.md](https://agents.md) para dar contexto e instrucciones a agentes de codificación (Claude Code, Codex, Copilot, etc.) que trabajen en este repositorio.

## Sobre este repositorio

`Dennis-Superpowers` es una colección personal de skills (capacidades reutilizables) para agentes de codificación. Cada skill vive en `skills/<nombre-skill>/` con un `SKILL.md` que describe cuándo y cómo usarla.

## Estructura

```
Dennis-Superpowers/
├── AGENTS.md          # este archivo
├── CLAUDE.md          # enlaza aquí
├── README.md
└── skills/
    └── <nombre-skill>/
        └── SKILL.md
```

## Reglas

1. **No firmar ni dejar marcas de autoría del modelo/harness en Git o GitHub.** Los commits, mensajes de commit, pull requests, comentarios y cualquier otra acción realizada sobre este repositorio (o en su nombre) no deben incluir menciones de coautoría del modelo, del harness, ni marcas de agua similares (por ejemplo, líneas tipo "Co-Authored-By: Claude" o "Generated with ..."). La autoría del trabajo se atribuye únicamente al usuario.

## Cómo trabajar en este repo

- Antes de crear o modificar una skill, revisa si ya existe una similar en `skills/`.
- Mantén cada `SKILL.md` autocontenido: debe explicar el propósito de la skill, cuándo activarla y cómo usarla, sin depender de contexto externo no versionado.
- Los cambios estructurales (renombrar carpetas, mover skills) deben mantener la convención `skills/<nombre-skill>/SKILL.md`.
