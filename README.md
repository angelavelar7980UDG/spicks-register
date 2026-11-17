# Spicks Register

Registro personal de apuestas en pesos mexicanos (MXN) con cuota decimal. Lleva ganancia, pérdida,
inversión propia y reinversión de ganancias. Funciona como app en el iPhone y también sin internet.

## Publicarla (una sola vez)

1. En este repositorio: **Settings → Pages**.
2. En *Build and deployment*, elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y guarda.
3. En uno o dos minutos GitHub muestra la dirección, algo como `https://TU-USUARIO.github.io/spicks-register/`.

> GitHub Pages es gratis en repositorios públicos. En uno privado requiere un plan de pago.
> Aquí no hay datos tuyos: todo se guarda en tu dispositivo, no en el repositorio.

## Instalarla en el iPhone

1. Abre la dirección en **Safari**.
2. Toca **Compartir → Añadir a pantalla de inicio → Añadir**.
3. Ábrela desde el ícono: se ve a pantalla completa, sin barra del navegador.

## Tus datos

- Se guardan **en ese iPhone**. No se sincronizan con otros dispositivos.
- La app instalada tiene su propio almacenamiento, separado de Safari. Instálala **antes** de capturar tus apuestas reales.
- Para cambiar de teléfono o tener una copia: menú **⋯ → Guardar respaldo (JSON)**, y en el otro dispositivo **Restaurar respaldo…**
- También puedes exportar a Excel desde **⋯ → Exportar a Excel (CSV)**.

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La app completa (sin librerías externas) |
| `manifest.webmanifest` | Nombre e íconos de la app instalada |
| `sw.js` | Modo sin conexión |
| `spicks_simbolo.svg`, `icons/` | Símbolo e íconos de Spicks |

Para actualizar la app, reemplaza los archivos y sube los cambios. Con internet, siempre abre la versión más nueva.
