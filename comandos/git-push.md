# Git push

El comando `git push` envía los commits del repositorio local a un repositorio remoto.

## Enviar una rama por primera vez

```bash
git push -u origin nombre-rama
```

La opción `-u` establece una relación entre la rama local y la remota.

## Enviar cambios posteriores

```bash
git push
```

## Ejemplo

```bash
git push -u origin feat/git-add
```

Antes de realizar un push, es necesario haber creado al menos un commit.
