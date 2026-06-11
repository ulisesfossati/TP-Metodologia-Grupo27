# Git merge

El comando `git merge` integra los cambios de una rama dentro de otra.

## Ejemplo

Primero nos ubicamos en la rama que recibirá los cambios :

```bash
git switch main
```

Después realizamos el merge:

```bash
git merge feat/git-add
```

## Resultado

Si las ramas no tienen cambios incompatibles, Git realiza la integración automáticamente.

Si ambas ramas modificaron las mismas líneas, puede producirse un conflicto que deberá resolverse manualmente.

## Commit de merge

En algunos casos, Git crea un commit especial que registra la unión de las ramas.
