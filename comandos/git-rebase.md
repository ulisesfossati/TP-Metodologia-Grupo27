# Git rebase

El comando `git rebase` permite trasladar los commits de una rama para que se apliquen sobre la versión más reciente de otra rama.

## Ejemplo

```bash
git switch feat/git-log
git rebase main
```

Git toma los commits de `feat/git-log` y los vuelve a aplicar después del último commit de `main`.

## Ventaja

Genera un historial más lineal y fácil de leer.

## Precaución

No se recomienda hacer rebase sobre una rama compartida si otros integrantes ya están trabajando con esos commits, porque el rebase modifica sus hashes.
