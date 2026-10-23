# Atril Cámara

Teleprompter con cámara para grabar VSL y videos en el mismo celular. Se usa en https://adesentis.github.io/atril/ (Chrome en Android).

- **Los videos no se suben a ningún lado:** se graban en el navegador y se guardan en Descargas del celular.
- **Este repositorio es público.** El código y los guiones de `guiones/` los puede ver cualquiera con el link. Los guiones que pegas en el celular con "Pegar guion" se quedan solo en ese celular.

## Agregar un guion para todos los dispositivos
1. Crear `guiones/<nombre>.json` con `{"titulo": "...", "texto": "...", "actualizado": "AAAA-MM-DD"}`.
2. Agregar el nombre del archivo a `guiones/indice.json`.

Formato del texto: `##` bloque · `###` toma · `####` etiqueta que no se lee · `[CLIP …]` indicación donde el texto se detiene (la grabación sigue).

Versión sin cámara, con guiones privados sincronizados: el artifact "Atril VSL" en Claude. Fuente: `Infoproducto Hotselling/herramientas/atril/`.
