# LoteTUN

Aplicación independiente para consultar fecha, lote juliano, semana del año, vencimiento configurable y calendario mensual.

## Archivos

- `index.html`: aplicación principal.
- `manifest.json`: configuración PWA.
- `sw.js`: funcionamiento sin conexión.
- `icon.svg`: ícono de la aplicación.

## Formatos actuales

- Lote del día: `DDDYY`, por ejemplo `20926`.
- Semana del año: `WWYY-DD`, por ejemplo `3126-28`.

La configuración de días para vencimiento se guarda con la clave independiente `lotetun-days` y no comparte datos con LoteSUB.
