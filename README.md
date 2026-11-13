# Cal y Píxel

Herramienta web para convertir fotos en texturas y sprites del juego con una receta fija:
encuadre, quitar fondo, niveles, paso alto, mediana, contraste en S, reducción a píxeles,
posterizado y paleta por fase. Incluye un modo Boss en alta resolución con tonos planos
y un modo Paisaje para fondos, con neblina de lejanía.

## Capas

- Importa una carpeta, un zip o varias imágenes: cada imagen entra en su propia capa.
- Cada capa hereda los ajustes del diseño principal o lleva valores propios.
- Las piezas se mueven arrastrando, se escalan tirando de las esquinas, se voltean y se ocultan.
- Crear y borrar capas, añadir y quitar piezas en un diseño ya empezado.
- Organizar todo en un tilemap de celdas de 16, exportar la composición tal como está
  o exportar cada pieza por separado en un zip (con su tamaño original si hace falta).
- Deshacer (Ctrl+Z), rehacer (Ctrl+Y), cortar (Ctrl+X), copiar (Ctrl+C) y pegar (Ctrl+V).

Todo se procesa en el navegador: las fotos no se suben a ningún sitio.

Publicada con GitHub Pages desde la rama `main`, carpeta raíz.
