# Git log

El comando `git log` permite consultar el historial de commits de un repositorio.

## Uso básico

```bash
git log
```

Muestra el hash, autor, fecha y mensaje de cada commit.

## Vista resumida

```bash
git log --oneline
```

## Ver todas las ramas

```bash
git log --oneline --all --graph --decorate
```

## Ver cambios de cada commit

```bash
git log --stat
```

Este comando es útil para analizar la evolución del proyecto y obtener estadísticas.
