# Empleado del Mes poderNET

Juego 3D de 2 jugadores en la oficina de poderNET en San Luis Potosí. Dos compañeros compiten por ser el empleado del mes: mantén trabajando a Debi, Toño, Diana, Luis, Felipe, Brenda, Suemmy, Isai, Eli y Gallegos, levanta la red en el NOC y junta más puntos que el otro. Pero cuidado: cuando lleguen Cerón, el CEO, o Deysimar, la gerente, hay que correr. Y en Halloween también se aparece la niña fantasma.

## Cómo jugar

Abre `index.html` en el navegador o súbelo a cualquier hosting estático (Vercel, sin configuración). Necesita internet para cargar Three.js. Cada partida dura 1 minuto 50 segundos.

| | Moverse | Grito |
|---|---|---|
| Jugador 1 | W A S D | F o Espacio |
| Jugador 2 | Flechas | Enter o L |

- Empleado de flojo: +10
- Levantar la red en el NOC: +25
- El grito (¡VAMOS!) despierta a los que estén cerca y aturde al otro jugador
- El café te hace correr más rápido
- **Cerón, el CEO**: te persigue. Si te alcanza te regaña: −30 y te congela. No le grites (−10)
- **Deysimar, la gerente**: va tras el que va ganando. Si te alcanza te regaña: −30 y te congela. No le grites (−10)
- **La niña fantasma**: apaga las luces y espanta a la banda. Si te toca: −10. Grítale dos veces y se esfuma: +20
- Si la productividad llega a 0, Cerón y Deysimar los corren a los dos
- Al ganador, toda la banda se levanta a aplaudirle y Cerón y Deysimar le entregan el trofeo de empleado del mes
- Todos los empleados usan la chamarra negra de poderNET; cada jugador lleva un parche y un aro de su color

## Música del ganador

Al ganar suena un himno épico compuesto dentro del juego (sin derechos de autor). Si quieres otra canción, sube un archivo `musica-ganador.mp3` a la raíz del repo y el juego la usará en su lugar (con loop). Usa música libre de derechos, por ejemplo de Pixabay Music.

## Archivos

- `index.html`: el juego (HTML, CSS y JavaScript con Three.js r128)
- `logo.js`: logo de poderNET incrustado en base64
- `logo-podernet.png`: logo original
