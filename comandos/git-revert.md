# Git revert

El comando `git revert` deshace los cambios de un commit mediante la creación de un commit nuevo.

## Sintaxis

```bash
git revert HASH_DEL_COMMIT
```

## Ejemplo

```bash
git revert a1b2c3d
```

Git crea un commit que aplica los cambios opuestos al commit seleccionado.

## Diferencia con git reset

- `git revert` conserva el historial y es seguro para ramas compartidas.
- `git reset` puede modificar o eliminar parte del historial local.

Para este trabajo práctico se debe realizar al menos un revert.
