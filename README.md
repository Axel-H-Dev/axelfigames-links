# AxelfiGames Links

Página estática y responsive para compartir las redes de AxelfiGames. No necesita backend ni base de datos.

## Ver en tu computadora

Abrí `index.html` en tu navegador. Necesitás internet solo para cargar la tipografía de Google; el resto funciona localmente.

## Publicar gratis con GitHub Pages

1. Creá un repositorio público, por ejemplo `axelfigames-links`.
2. Subí `index.html`, `style.css`, `script.js` y la carpeta `assets` a la raíz.
3. En Settings > Pages, elegí `Deploy from a branch`, rama `main`, carpeta `/ (root)`.
4. Tu página quedará en `https://TU_USUARIO.github.io/axelfigames-links/`.

## Publicar en Fly.io

Se incluye un `Dockerfile` para alojarla con Nginx. En Fly.io se puede ejecutar `fly launch` y `fly deploy`, después de instalar flyctl y configurar tu cuenta. Fly.io no garantiza hosting gratuito permanente para cuentas nuevas: verificá sus costos.

## Personalizar

- Redes sociales y textos: `index.html`.
- Colores, fuentes y efectos: `style.css`.
- Avatar: reemplazá `assets/avatar.webp`.
- Alias: buscá `axel.mdpp` en `index.html`.
- PayPal: no se incluyó enlace porque no se proporcionó una URL de cobro verificada.

Nota: el enlace de YouTube incluye `sub_confirmation=1`, que puede mostrar una confirmación según el dispositivo. Las demás redes abren el perfil para que la persona siga el canal manualmente.
