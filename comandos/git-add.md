# Git add

El comando `git add` agrega cambios al área de preparación, también conocida como *staging area*. Esto permite seleccionar qué modificaciones se incluirán en el próximo commit.

## Agregar un archivo específico

```bash
git add indice.md
```

## Agregar varios archivos

```bash
git add git-init.md git-clone.md
```

## Agregar todos los cambios

```bash
git add .
```

## Importante

`git add` no crea un commit. Solamente prepara los cambios para que luego sean registrados con `git commit`.
