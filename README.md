# Empleado del Mes poderNET

Juego 3D de 2 jugadores en la oficina de poderNET en San Luis Potosí. Dos compañeros compiten por ser el empleado del mes: mantén trabajando a Debi, Toño, Diana, Luis, Felipe, Brenda, Suemmy, Isai, Eli y Gallegos, levanta la red en el NOC y junta más puntos que el otro. Pero cuidado: cuando lleguen Cerón, el CEO, o Deysimar, la gerente, hay que correr. Y en Halloween también se aparece la niña fantasma.

## Cómo jugar

Abre `index.html` en el navegador o súbelo a cualquier hosting estático (Vercel, sin configuración). Necesita internet para cargar Three.js. Cada nivel dura 1 minuto 50 segundos.

## Explorar la oficina

Al abrir el juego entras a la oficina en modo libre: caminas con WASD o flechas (en celular, con el dedo en el piso) y la cámara te sigue. Acércate a alguien y presiona **E** (en celular, el botón **Platicar**) para platicar con la banda, con Cerón y con Deysimar. También puedes meterte al **almacén**, donde duerme la rata come-cables, y revisar el NOC, la planta de luz y los garrafones.

Cuando estés listo, presiona **Empezar a trabajar** para elegir entre 2 jugadores o contra la CPU. Al terminar una partida puedes volver a explorar.

## Niveles

Son 3 niveles de 1:50; los puntos se van sumando. Cada nivel agrega un enemigo nuevo:

1. **Cerón, el CEO**, **Deysimar, la gerente** y **la niña fantasma**.
2. **El cliente enojado**: tumba la red al llegar y te persigue para quejarse (−20). Levanta la red en el NOC y se va contento (+15). Al cliente no se le grita (−10).
3. **La rata come-cables**: sale del almacén y va al NOC a morder los cables. Atrápala antes de que llegue (+25).

El NOC tiene 4 racks y un video wall con dos cámaras de seguridad en vivo, gráficas de tráfico, sensores, mapa de nodos, alertas y tickets.

| | Moverse | Grito |
|---|---|---|
| Jugador 1 | W A S D | F o Espacio |
| Jugador 2 | Flechas | Enter o L |

- Empleado de flojo: +10
- Levantar la red en el NOC: +25
- El grito (¡VAMOS!) despierta a los que estén cerca y aturde al otro jugador
- El café te hace correr más rápido
- **Combos**: despierta empleados seguidos (menos de 6 s entre uno y otro). Desde el 3.º valen +15 y desde el 6.º +20. Si te regañan o te espantan, se pierde la racha
- **Poderes en el piso**: Fibra (corres al doble), Antena (grito al doble de lejos), Gafete (los jefes y el cliente no te agarran) y WiFi (despiertas solo a quien pases cerca)
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
