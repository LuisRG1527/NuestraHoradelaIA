# Lotería de la IA

Versión MVP funcional para una dinámica virtual.

## Cómo jugar
1. Sube `index.html` a un hosting estático con HTTPS (por ejemplo GitHub Pages, Netlify o Vercel).
2. Abre la página en la computadora del anfitrión.
3. El anfitrión pulsa "Soy anfitrión" → "Crear sala".
4. Comparte el código IA-XXXX con los participantes.
5. Cada participante entra desde su celular/computadora, escribe su nombre y el código.
6. El anfitrión saca las cartas.
7. Cada jugador DEBE dar clic a la casilla cuando aparece la carta.
8. Si se le pasa una carta, no queda marcada automáticamente.
9. Al completar su tablero, pulsa "¡LOTERÍA!".
10. El anfitrión recibe la reclamación y se valida.

## Nota técnica
La comunicación entre dispositivos usa PeerJS para señalización WebRTC. Se necesita conexión a internet y servir la página por HTTPS. No requiere cuentas ni una base de datos propia para este MVP.

## Próximas mejoras sugeridas
- Sonidos de lotería y animaciones.
- Baraja de 54 cartas.
- Cartas especiales.
- Panel de anfitrión con historial de cartas.
- Ranking y contador de tiempo.
- Branding de la empresa.
- Carga de logos/colores.
