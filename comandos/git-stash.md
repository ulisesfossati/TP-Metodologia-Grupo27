# Git stash

El comando `git stash` sirve para guardar temporalmente cambios que todavía no queremos incluir en un commit.

Es útil cuando estamos trabajando en algo, pero necesitamos cambiar de rama sin perder lo que hicimos.

## Guardar cambios

```bash
git stash
```

Este comando guarda los cambios realizados y deja la carpeta de trabajo limpia.

## Ver los cambios guardados

```bash
git stash list
```

Muestra una lista de los cambios guardados temporalmente.

## Recuperar los cambios

```bash
git stash pop
```

Recupera los últimos cambios guardados y los elimina de la lista de stash.

También se puede usar:

```bash
git stash apply
```

Este comando recupera los cambios, pero los mantiene guardados en la lista.

## Eliminar un stash

```bash
git stash drop
```

Elimina el último cambio guardado.

## Ejemplo de uso

```bash
git stash
git switch dev
git pull origin dev
git switch ulises
git stash pop
```

En este ejemplo, primero se guardan los cambios, luego se actualiza la rama `dev` y finalmente se recuperan los cambios en la rama de trabajo.

### [Volver al índice](../indice.md)
