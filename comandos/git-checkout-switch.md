# Git checkout y Git switch

Los comandos `git checkout` y `git switch` permiten cambiar de rama.

## Cambiar de rama con checkout

```bash
git checkout nombre-rama
```

## Crear una rama y cambiarse a ella

```bash
git checkout -b feat/git-status
```

## Cambiar de rama con switch

```bash
git switch nombre-rama
```

## Crear una rama con switch

```bash
git switch -c feat/git-status
```

`git switch` fue creado específicamente para trabajar con ramas, mientras que `git checkout` también puede utilizarse para otras operaciones.
