# Cómo entrar al Muro Wonderlust en modo equipo

El muro vive en este repositorio y se publica en GitHub Pages. Cualquiera con el link lo ve. Para colgar cosas (post-its, fotos, videos, mover piezas, editar el brand book) necesitas dos cosas: ser colaborador del repositorio y un token de GitHub.

## 1. Que Paula te agregue como colaborador

Paula entra a **Settings → Collaborators** del repositorio y agrega tu usuario de GitHub. Te llega una invitación por correo; acéptala.

Si no tienes cuenta de GitHub, créala en github.com (es gratis) y pásale tu usuario a Paula.

## 2. Crea tu token

1. Entra a https://github.com/settings/tokens/new (es un "classic token"; los tokens "fine-grained" no sirven para repositorios de otra persona).
2. En **Note** escribe algo como `muro wonderlust`.
3. En **Expiration** elige 90 días o "No expiration".
4. En **Select scopes** marca solo **public_repo**.
5. Baja y pulsa **Generate token**.
6. Copia el token (empieza por `ghp_`). GitHub lo muestra una sola vez; si lo pierdes, generas otro.

## 3. Entra al muro

1. Abre el muro y pulsa **Modo equipo**.
2. Escribe tu nombre (es la firma que queda en lo que cuelgas) y pega el token.
3. Pulsa **Entrar**. El muro comprueba que el token sirve y que tienes permiso de escritura.

El token queda guardado solo en tu navegador. Si cambias de computador, vuelves a pegarlo.

## Qué pasa cuando cuelgas algo

Cada cambio se guarda como un commit en este repositorio, firmado con tu usuario de GitHub. Las fotos y videos que arrastras quedan en la carpeta `u/`; el resto (post-its, posiciones, textos editados) queda en `data/snapshot.json`.

El punto de color al lado del logo te dice cómo va: verde es guardado, amarillo está guardando, rojo es que algo falló (pasa el mouse para ver el motivo).

Quien entra con token ve los cambios de los demás casi al instante. Quien solo tiene el link los ve unos minutos después, porque GitHub Pages tarda en republicar.

## Límites

- Fotos: se reducen a 1600 px antes de subir, así que pesan poco.
- GIF y video: se suben tal cual, máximo 45 MB por archivo. Si un video pesa más, comprímelo antes.
- Si dos personas mueven la misma pieza al mismo tiempo, gana el último que guarda.

## Si algo falla

- "El token no es válido o venció": genera uno nuevo.
- "No tienes permiso de escritura": revisa que aceptaste la invitación de colaborador.
- Punto rojo que no se quita: recarga la página; si sigue, avísale a Paula.
