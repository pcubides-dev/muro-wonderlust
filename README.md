# Muro Wonderlust

Moodboard interactivo de la marca Wonderlust. Se publica con GitHub Pages desde la rama `main`.

- `index.html` — el muro.
- `a/` — fotos, fuentes y videos de los capítulos.
- `kit/` — el kit de marca completo (se abre dentro del muro y en `kit/index.html`); `kit/descargas/` tiene los zips para el equipo.
- `u/` — lo que el equipo cuelga (fotos, gifs, videos). No borrar a mano: el muro guarda aquí.
- `data/snapshot.json` — post-its, posiciones, textos editados y casos. Lo escribe el muro.

Para entrar en modo equipo lee [COMO-ENTRAR.md](COMO-ENTRAR.md).

## Publicar

No hay que hacer nada. Cada cambio del equipo es un commit y GitHub Pages republica solo en uno o dos minutos.

## Si hay que tocar el código

El muro se genera desde `index.html` del artifact original con `build_gh.py` (está en la sesión de Claude de Paula). Editar directamente `index.html` también sirve; lo único que no se puede tocar a mano es `data/snapshot.json` mientras alguien esté colgando cosas.
