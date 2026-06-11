# Git remote

El comando `git remote` permite administrar las conexiones entre el repositorio local y los repositorios remotos.

## Ver repositorios remotos

```bash
git remote -v
```

## Agregar un repositorio remoto

```bash
git remote add origin https://github.com/usuario/tp-git.git
```

## Cambiar la URL

```bash
git remote set-url origin NUEVA_URL
```

## Eliminar un remoto

```bash
git remote remove origin
```

Por convención, el repositorio remoto principal suele llamarse `origin`.
