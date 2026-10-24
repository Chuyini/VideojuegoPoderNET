# Jefes de poderNET 3D

Juego 3D de 2 jugadores en la oficina de poderNET en San Luis Potosí. Pon a jalar a Debi, Toño, Diana, Luis, Felipe, Brenda, Suemmy, Isai, Eli y Gallegos, levanta la red en el NOC y demuestra quién es el mejor jefe. Pero cuidado: Cerón, el CEO, te persigue, y Deysimar, la gerente, mete a la banda a sus juntas.

## Cómo jugar

Abre `index.html` en el navegador o súbelo a cualquier hosting estático (Vercel, sin configuración). Necesita internet para cargar Three.js.

| | Moverse | Grito |
|---|---|---|
| Jugador 1 | W A S D | F o Espacio |
| Jugador 2 | Flechas | Enter o L |

- Empleado de flojo: +10
- Levantar la red en el NOC: +25
- El grito despierta a los que estén cerca y aturde al otro jefe
- El café te hace correr más rápido
- **Cerón, el CEO**: te persigue; si te alcanza, −30 y te congela. Si le gritas, −10
- **Deysimar, la gerente** (esposa del CEO): mete a los empleados a juntas; si te alcanza te pide un reporte, −15. Grítale y se va a otra junta: +15
- Si la productividad llega a 0, Cerón los corre a los dos

## Archivos

- `index.html`: el juego (HTML, CSS y JavaScript con Three.js r128)
- `logo.js`: logo de poderNET incrustado en base64
- `logo-podernet.png`: logo original
