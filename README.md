# Buda Ishii

Juego web pixel art en el que Ishii construye escuelas, hospitales, universidades, centros de jubilados, laboratorios, polos tecnológicos y otras obras mientras se defiende de monstruos lanzando libros.

La campaña tiene tres niveles de 4, 6 y 8 obras. Cada mapa es más amplio, tiene una ambientación diferente y aumenta progresivamente la velocidad, frecuencia y resistencia de los enemigos.

En cada etapa podés elegir entre dos obras disponibles. Al terminar todas, comienza una oleada final con un jefe. Hay enemigos ágiles, pesados y lanzadores, música y efectos de sonido. El resultado final muestra tiempo, obras, enemigos derrotados y puntaje; el récord queda guardado en el navegador.

La interfaz está diseñada primero para celulares: el mapa conserva su relación de aspecto, ocupa todo el ancho y se integra con un panel inferior ambiental, sin barras negras. Permite moverse, construir y disparar simultáneamente con varios dedos. En mobile, los libros cuentan con una asistencia de apuntado moderada.

La dirección visual, los mapas, el personaje, los enemigos, los edificios, los libros y los efectos se integraron a partir del Artbook/GDD de octubre de 2026.

Cada obra otorga un beneficio: construcción más rápida, recuperación de confianza, puntos adicionales, resistencia, mayor daño, disparo más rápido o velocidad de movimiento. La explicación completa está en el botón **BENEFICIOS** dentro del juego.

La pérdida de confianza aumenta progresivamente entre niveles. Ishii y los tres tipos de enemigo utilizan spritesheets de 12 fotogramas, con estados de caminata, reposo, ataque, daño y construcción o derrota. Los enemigos siempre se orientan hacia Ishii.

## Controles

- Flechas o WASD: moverse
- Espacio: construir
- Ctrl: lanzar libros
- Shift: esquivar
- M: activar o desactivar el sonido
- En celular aparecen controles táctiles independientes para construir, lanzar libros y esquivar.

## GitHub Pages

En GitHub: **Settings → Pages → Deploy from a branch → main → /(root)**.
