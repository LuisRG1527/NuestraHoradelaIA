# Lotería de la IA · V8

Cambios:
- Las 54 cartas están embebidas dentro de `index.html` como imágenes WebP de alta calidad.
  Esto evita que GitHub Pages deje las cartas en blanco por rutas relativas.
- Se aplica un sharpening moderado a las cartas antes de integrarlas.
- El QR genera una URL con `?modo=jugador&sala=IA-XXXX`.
- Al abrir esa URL, la página entra directamente a la pantalla de jugador y deja la sala prellenada.
- El campo de sala comienza con `IA-`.
- No se muestra la baraja debajo de las páginas.
- El jugador sigue teniendo sus cartas ocultas hasta que el anfitrión inicia.
- La única forma de ganar es completar las 16 casillas.
