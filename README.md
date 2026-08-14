# Lotería de la IA · V11 Firebase

Esta versión reemplaza PeerJS/WebRTC por Firebase Realtime Database.

## Configuración
- Firebase project: `loteria-ia`
- Realtime Database: `https://loteria-ia-default-rtdb.firebaseio.com/`
- Las cartas permanecen embebidas en el HTML.
- GitHub Pages solo necesita `index.html`.

## Flujo
1. Anfitrión entra con `HoraIA-BBVA`.
2. Crea una sala `IA-XXXX`.
3. Jugadores entran por código o QR.
4. El anfitrión pulsa **Iniciar juego**.
5. Las cartas se cantan desde Firebase y se sincronizan con todos.
6. Cada jugador solo puede marcar cartas que ya fueron cantadas.
7. Players se actualiza con el progreso.
8. Gana quien completa 16/16 y canta **¡LOTERÍA!**.

## Importante
La primera prueba puede usar Realtime Database en Test Mode. Antes de una sesión real conviene configurar reglas de seguridad.
