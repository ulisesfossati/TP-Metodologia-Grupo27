# Resolución de conflictos

Un conflicto ocurre cuando Git no puede integrar automáticamente dos cambios porque afectan la misma parte de un archivo.

## Ejemplo de conflicto

```text
<<<<<<< HEAD
Texto de la rama actual
=======
Texto de la otra rama
>>>>>>> feat/otra-rama
```

## Pasos para resolverlo

1. Abrir el archivo en conflicto.
2. Elegir qué contenido conservar.
3. Eliminar las marcas `<<<<<<<`, `=======` y `>>>>>>>`.
4. Guardar el archivo.
5. Agregarlo al área de preparación.
6. Finalizar el merge o rebase.

```bash
git add archivo.md
git commit -m "fix: resolver conflicto en archivo"
```

## Requisito del trabajo

Antes de resolver el conflicto, se debe sacar una captura de pantalla y anotar el hash del commit asociado.

## Hash del commit del conflicto

Completar con el valor real:

```text
Hash: PENDIENTE
```

## Captura

Guardar la imagen dentro de una carpeta llamada `imagenes` e insertarla así:

```md
![Conflicto antes de resolver](imagenes/conflicto.png)
```
