# PAC-FAMILY

Videojuego arcade familiar para navegador. Está construido con HTML5, CSS3, JavaScript, Canvas 2D y LocalStorage; no necesita frameworks ni dependencias.

## Ejecutar
Abre `index.html` en un navegador moderno. Para publicar, sirve los cuatro archivos desde la raíz de un sitio estático.

## Controles
- Jugador 1: flechas del teclado.
- Jugador 2: W, A, S, D.
- Pausa: barra espaciadora o botón II.
- Celular: botones táctiles y gesto de deslizamiento sobre el laberinto.

## Incluye
- Modo individual y dos jugadores en el mismo equipo.
- Cinco niveles, cuatro fantasmas, puntos, poderes y tres vidas por jugador.
- Marcadores, pausa, reinicio y pantallas de victoria/derrota.
- Clasificación local guardada en el navegador.
- Diseño adaptable y efectos de sonido generados por Web Audio API.

## Despliegue en Vercel
Importa este repositorio desde Vercel. Selecciona **Other** como Framework Preset, deja Build Command vacío, usa la raíz del repositorio como Root Directory y Output Directory. No requiere variables de entorno ni instalación. Con la integración GitHub–Vercel activa, cada push a la rama de producción actualiza el sitio.

## Personalizar
- `index.html`: estructura y textos.
- `style.css`: colores y diseño.
- `script.js`: laberinto, reglas, velocidad, puntuación y controles.

Los récords se almacenan en el navegador con la clave `pacFamilyScores`; no se sincronizan entre dispositivos.