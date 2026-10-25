# Isla Salvaje

Prototipo de supervivencia para navegador, con arte pixelado de aventura.

## Jugar y crear

- Abre index.html para jugar.
- editor.html permite pintar mapas, importar sprites PNG, guardar proyectos JSON o descargar imágenes.
- asset-creator.html permite dibujar sprites, NPC y animales animados en cuatro direcciones; también permite crear casas y otros edificios.
- Los personajes y animales pueden usar 3, 4, 6 u 8 cuadros de animación por dirección.
- El PNG exportado es una hoja de sprites con filas en orden abajo, izquierda, derecha y arriba.

## Carpetas de recursos

- assets/maps: proyectos de mapa exportados desde el editor.
- assets/sprites: personajes, árboles, rocas, herramientas y muebles.
- assets/npcs: hojas de personajes no jugadores.
- assets/animals: sprites y animaciones de animales.
- assets/buildings: casas, refugios y otros edificios.
- assets/tilesets: conjuntos de cuadros de terreno.

Los mapas exportados se pueden guardar en assets/maps. La carga automática de mapas al iniciar el juego todavía requiere conectar el juego con esos archivos. Para recursos estáticos, el PNG se guarda en la carpeta correspondiente. El proyecto JSON del creador conserva los cuadros para seguir editándolos.

## Publicar

GitHub Pages se configura en Settings → Pages → Source: GitHub Actions.
