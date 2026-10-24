# Jefes de poderNET 3D

Juego 3D de 2 jugadores en la oficina de poderNET en San Luis Potosí. Pon a jalar a Debi, Toño, Diana, Luis, Felipe, Brenda, Suemmy, Isai, Eli y Gallegos, levanta la red en el NOC y demuestra quién es el mejor jefe. Pero cuidado: cuando lleguen Cerón, el CEO, o Deysimar, la gerente, hay que correr. Y en Halloween también se aparece la niña fantasma.

## Cómo jugar

Abre `index.html` en el navegador o súbelo a cualquier hosting estático (Vercel, sin configuración). Necesita internet para cargar Three.js. Cada partida dura 3 minutos.

| | Moverse | Grito |
|---|---|---|
| Jugador 1 | W A S D | F o Espacio |
| Jugador 2 | Flechas | Enter o L |

- Empleado de flojo: +10
- Levantar la red en el NOC: +25
- El grito despierta a los que estén cerca y aturde al otro jugador
- El café te hace correr más rápido
- **Cerón, el CEO**: te persigue. Si te alcanza te regaña: −30 y te congela. No le grites (−10)
- **Deysimar, la gerente**: va tras el que va ganando. Si te alcanza te regaña: −30 y te congela. No le grites (−10)
- **La niña fantasma**: apaga las luces y espanta a la banda. Si te toca: −10. Grítale dos veces y se esfuma: +20
- Si la productividad llega a 0, Cerón y Deysimar los corren a los dos

## Archivos

- `index.html`: el juego (HTML, CSS y JavaScript con Three.js r128)
- `logo.js`: logo de poderNET incrustado en base64
- `logo-podernet.png`: logo original
