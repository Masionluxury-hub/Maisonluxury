# Maison Luxury

Catálogo estático de fragancias D'Oban Parfums.

## Publicar y actualizar desde GitHub

1. Sube la imagen editada y optimizada a la carpeta `catalogo/`.
2. Añade o actualiza la ficha correspondiente en `catalog.js`.
3. Para cambiar un precio, modifica solo el valor de `price`. Para retirar una fragancia, elimina su bloque del arreglo.
4. Publica los cambios del repositorio con el flujo habitual de GitHub.

La imagen de cada producto contiene su descripción y notas. Fuera de la imagen solo se muestran nombre, referencia, familia y valor. La selección del visitante solo se marca en pantalla; no abre WhatsApp, no envía mensajes y no crea pedidos.

## Vista previa local

- Abre `index.html` para consultar el catálogo publicado en `catalog.js`.
- Abre `index.html?admin=1` para ensayar altas, cambios de valor o eliminaciones en ese navegador.
- Los cambios hechos desde esta vista se guardan como borrador local; para publicarlos hay que trasladarlos a `catalog.js` y subir la imagen a `catalogo/`.

## Limitaciones de esta versión

La selección del visitante y los borradores del panel se guardan en `localStorage`: solo existen en ese navegador y dispositivo. El catálogo compartido siempre proviene de `catalog.js` y se actualiza manualmente en GitHub.

El acceso `?admin=1` simplifica la demostración local, pero no es autenticación ni protege los cambios. No debe considerarse un panel administrativo seguro mientras no exista un backend.
