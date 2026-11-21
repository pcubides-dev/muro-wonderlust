# El umbral como sistema

La puerta y los haces son fijos. Lo que cambia es la silueta que la cruza.

- `umbral_vacio_*.svg`: solo la puerta con la luz. Sirve de marco para anunciar y revelar contenidos.
- `umbral_trex_*.svg`: la silueta base (el logo).
- `umbral_director_*`, `umbral_camarografo_*`, `umbral_flotando_*`, `umbral_trofeo_*`, `umbral_isla_*`: otras siluetas en el mismo hueco (generadas con Higgsfield; el trazado limpio de cada una está en `siluetas/`).

Para hacer una silueta nueva: la figura va como trazado negro dentro de la máscara (es un hueco en la puerta, no una forma encima),
apoyada en el borde inferior del vano (y = 330 a 380 en el sistema de coordenadas del archivo), mirando hacia la luz.
Reglas: una sola silueta, sin detalles finos menores a 4 unidades, nunca en color: siempre es un hueco.
