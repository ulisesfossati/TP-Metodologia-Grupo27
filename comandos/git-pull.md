# Git pull

El comando `git pull` descarga los cambios del repositorio remoto y los integra en la rama local actual.

## Sintaxis

```bash
git pull origin main
```

En muchos casos, si la rama ya está vinculada con su versión remota, alcanza con:

```bash
git pull
```

## Funcionamiento

`git pull` combina dos operaciones:

1. Descarga los cambios mediante `git fetch`.
2. Los integra mediante `git merge`.

Es recomendable ejecutarlo antes de comenzar a trabajar para tener la versión más actualizada.
