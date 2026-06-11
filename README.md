# ⚽🍺 Juego de Beber del Mundial 2026

Aplicación web para jugar al juego de beber mientras veis partidos del Mundial 2026. Sin instalación, sin servidor — abre el HTML y a jugar.

**[▶ Jugar ahora](https://kikinha113.github.io/worldcup2026)**

-----

## ¿Cómo funciona?

1. **Elige el partido** que estáis viendo (todos los 48 partidos de fase de grupos incluidos)
1. **Indica cuántos jugáis** (2 a 10 personas) y ponéis vuestros nombres
1. **Sorteo automático** — cada persona recibe un jugador real de cada equipo, repartido aleatoriamente para que nadie elija siempre al delantero estrella
1. **¡A jugar!** La app tiene todo lo que necesitáis durante el partido

## Pantallas durante el partido

|Pestaña    |Qué tiene                                                           |
|-----------|--------------------------------------------------------------------|
|👥 Jugadores|Tus asignaciones con posición, botón para cambiar si hay sustitución|
|📋 Reglas   |Todas las normas siempre a mano                                     |
|🃏 Comodines|Un comodín por persona por parte para saltarse una regla            |
|⚡ Extra    |Temporizador VAR, contador de chupitos, votación MVP del descanso   |

## Reglas del juego

### Acciones básicas

|Acción                       |Norma                        |
|-----------------------------|-----------------------------|
|Pase completado de tu jugador|Bebes 1 sorbo                |
|Pase fallado de tu jugador   |Bebe la persona de tu derecha|
|Disparo de tu jugador        |Todos beben 1 sorbo          |
|Disparo a puerta             |El dueño reparte 3 sorbos    |
|**GOL**                      |**Todos hacen chupito**      |
|Asistencia                   |El dueño reparte 5 sorbos    |
|Tarjeta amarilla             |El dueño bebe 3 sorbos       |
|Tarjeta roja                 |El dueño acaba su bebida     |
|Fuera de juego               |El dueño bebe 2 sorbos       |
|Falta cometida               |Bebes 2 sorbos               |
|Falta recibida               |Repartes 2 sorbos            |
|Córner provocado             |Repartes 3 sorbos            |
|Parada del portero           |El dueño reparte 3 sorbos    |
|¡Paradón!                    |El dueño reparte 5 sorbos    |

### Normas especiales

- **VAR** — Todos en silencio. Si cambia la decisión: todos beben. Cada 30s de espera: 1 sorbo (la app tiene temporizador automático)
- **Celebración rara/cringe** — Todos beben 1 sorbo
- **Jugador exagerando caída** — El dueño bebe 2 sorbos
- **Comentarista dice** *“intensidad”, “transición”, “bloque bajo”* o *“partido muy táctico”* — Todos beben 1 sorbo
- **MVP del descanso** — Votación grupal; el dueño reparte 5 sorbos
- **Tu jugador es sustituido** — Puedes quedarte con el sustituto pagando 3 sorbos (botón en la app)

### Límites de seguridad

- Máximo **3 sorbos** por persona por minuto
- **1 comodín** por parte para saltarse cualquier regla
- Máximo **3 chupitos** por partido — a partir del 3º los goles pasan a ser 3 sorbos
- En el descanso todos beben **agua**
- Debe haber **comida** en la mesa
- Se puede jugar con **agua o refresco** sin ningún problema
- **Si alguien quiere parar, se para. Sin discusión.**

## Datos incluidos

- 🌍 **48 selecciones** con plantillas reales del Mundial 2026
- ⚽ **48 partidos** de fase de grupos (todos los grupos A–L)
- 🔀 Sorteo aleatorio con posición del jugador (POR / DEF / CEN / DEL)

## Cómo usar

Descarga `index.html` y ábrelo en cualquier navegador. No necesita conexión a internet ni instalación.

Para acceder desde el móvil lo más cómodo es desplegarlo en GitHub Pages:

1. Sube `index.html` a tu repositorio como `index.html`
1. Ve a **Settings → Pages → Branch: main → Save**
1. GitHub te da una URL pública que funciona en cualquier dispositivo

## Tecnología

HTML + CSS + JavaScript puro. Sin dependencias, sin frameworks, sin servidor.

-----

> Beber siempre con moderación. Este juego es para mayores de edad.