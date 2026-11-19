# kiki.cl/vinilos

Repositorio de vinilos de Kiki: colección ("En la repisa") y lista de deseos.

- `vinilos.json` — fuente de verdad. `coleccion` y `deseos`; la página ordena sola (A–Z por artista, sin "The"; luego por año).
- `covers/<id>.jpg` — carátulas 640×640, recortadas de fotos propias.
- Discos de la lista de deseos sin `cover` se muestran con una carátula tipográfica.

Para agregar un disco: sumar la entrada en `coleccion` (con `cover`), sacarlo de `deseos` si estaba, y actualizar `actualizado`.
Campos opcionales: `edicion`, `nota` (estado del disco), `comentario`, `subartista`.
