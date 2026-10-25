# Empleado del Mes poderNET

Un juego en 3D de la oficina de poderNET en San Luis. Son dos compañeros peleándose el empleado del mes: hay que mantener a la banda trabajando, levantar la red cuando se cae y que no te cachen ni Cerón ni Deysimar echando hueva.

## Para jugar

Abre `index.html` en el navegador o súbelo a Vercel tal cual. Solo necesita internet para cargar Three.js.

Al abrirlo llegas a la oficina y puedes darte una vuelta antes de empezar: caminas con WASD o las flechas (en el cel, con el dedo) y platicas con quien quieras con E. Cuando te late, le das a **Empezar a trabajar** y eliges si juegas contra alguien o contra la computadora.

## La oficina

Es como el edificio de verdad: en la terraza del segundo piso hay dos puertas. La de la izquierda es la nave, con el site, el almacén y la banda. La de la derecha es la oficina de al lado, con Diana atendiendo clientes, Isai, Caro en facturación, el checador, la cafetera, el escritorio de Cerón y la sala de juntas, donde él les explica la red a unos socios con su pizarrón.

Mientras andas por ahí la gente no se está quieta: van por requisiciones con el almacenista, por agua, a checar, a revisar el site, a chismear o a la terraza, y de repente alguien se te acerca a platicar. En la terraza la señora de la limpieza va trapeando. Y si quieres, te sientas en tu escritorio.

## La partida

Son tres niveles de 1:50 y los puntos se van sumando.

| | Caminar | Gritar |
|---|---|---|
| Jugador 1 | W A S D | F o Espacio |
| Jugador 2 | Flechas | Enter o L |

- Si ves a alguien echando hueva, tócalo: +10.
- Si se cae la red, corre al site a levantarla: +25.
- Un grito despierta a todos los que estén cerca y de paso atonta al otro jugador.
- Si despiertas a varios seguidos haces combo: desde el tercero valen +15 y desde el sexto +20.
- En el piso salen café y poderes: Fibra (corres al doble), Antena (tu grito llega más lejos), Gafete (no te pueden agarrar) y WiFi (despiertas a quien pases cerca).

Y aguas con:

- **Cerón** y **Deysimar**: si te agarran te regañan (−30) y te quedas congelado. Y no se te ocurra gritarles (−10). Deysimar se va contra el que va ganando.
- **La niña fantasma**: apaga las luces y espanta a todos. Si te toca, −10. Con dos gritos se va (+20).
- **El cliente enojado** (nivel 2): tumba la red y se viene a quejar contigo (−20). Levántale la red y se va contento (+15).
- **La rata** (nivel 3): sale del almacén directo a morder los cables del site. Atrápala (+25).

Si la productividad llega a cero, los corren a los dos. Y al que gane... ya verá.

## Música

Toda la música está hecha dentro del juego, así que no hay broncas de derechos. Si quieres otra canción para cuando alguien gana, sube un `musica-ganador.mp3` a la raíz del repo y el juego la usa.

## Archivos

- `index.html`: el juego (HTML, CSS y JavaScript con Three.js r128)
- `logo.js`: el logo de poderNET incrustado
- `logo-podernet.png`: el logo original
