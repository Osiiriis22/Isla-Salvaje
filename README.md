# Isla Salvaje

Prototipo de supervivencia para navegador, con arte pixelado de aventura.

## Jugar y editar

- Abre index.html para jugar.
- Abre editor.html para pintar mapas, importar sprites PNG, guardar proyectos JSON o descargar imágenes.
- Las paletas de colores pueden importarse en formato GPL, PAL, HEX, TXT o JSON.
- Los proyectos del editor guardan dentro del JSON los sprites importados.

## Recursos del juego

- assets/maps: proyectos de mapas exportados desde el editor y el manifiesto de mapas.
- assets/sprites: personajes, árboles, rocas, herramientas y muebles.
- assets/npcs: sprites y animaciones de personajes no jugadores.
- assets/tilesets: conjuntos de cuadros de terreno.

Las carpetas organizan los recursos dentro del proyecto. El juego todavía debe conectarse al manifiesto para cargar mapas automáticamente; por ahora, los proyectos se guardan aquí como archivos.

## Publicar

GitHub Pages se configura en Settings → Pages → Source: GitHub Actions.
