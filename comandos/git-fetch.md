# Git fetch

El comando `git fetch` descarga la información más reciente del repositorio remoto, pero no modifica automáticamente la rama local.

## Sintaxis

```bash
git fetch origin
```

## Diferencia con git pull

- `git fetch` descarga los cambios sin integrarlos.
- `git pull` descarga e integra los cambios.

Después de ejecutar `git fetch`, podemos revisar los cambios antes de incorporarlos.

```bash
git log main..origin/main
```

Es útil cuando queremos verificar primero qué cambió en el remoto.
