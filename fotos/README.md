# Fotos del matrimonio

La galería de la portada lee `fotos.json`. Mientras esté vacío (`[]`),
la página muestra "Vienen en camino".

Formato:

```json
[
  { "src": "fotos/001.jpg", "thumb": "fotos/thumbs/001.jpg", "w": 800, "h": 1200, "alt": "Primer baile" }
]
```

- `src`: foto en tamaño para ver en pantalla (máx. ~2000 px de lado, JPG ~80 %).
- `thumb`: miniatura para la grilla (~800 px). Opcional.
- `w`/`h`: medidas de la miniatura; evitan saltos al cargar. Opcionales.
- `alt`: descripción corta. Opcional.

No subir los originales del fotógrafo (pesan demasiado para GitHub Pages);
siempre comprimir antes.
