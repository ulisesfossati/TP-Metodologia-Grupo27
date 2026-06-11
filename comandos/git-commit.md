# Git commit

El comando `git commit` registra de forma permanente los cambios que fueron agregados previamente al área de preparación.

Cada commit representa un punto del historial del proyecto y posee un identificador único llamado hash.

## Sintaxis

```bash
git commit -m "mensaje descriptivo"
```

## Ejemplo

```bash
git add git-status.md
git commit -m "feat: agregar explicación de git status"
```

## Buenas prácticas

- Escribir mensajes claros y descriptivos.
- Realizar commits pequeños y relacionados con una sola tarea.
- Utilizar Conventional Commits.
- No mezclar cambios sin relación en un mismo commit.
