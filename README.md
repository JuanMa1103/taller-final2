JUEGO DE AVENTURAS
Descripción: Este es un juego de rol por consola, donde el jugador avanza por un bosque mágico enfrentándose a diferentes enemigos. El objetivo final es derrotar al Mago Oscuro, responsable de la muerte del padre del protagonista.
El juego incluye
    * Selección de clases.
    * Sistema de combate por turnos.	
    * Diferentes tipos de enemigos.
	* Eventos aleatorios amigables.
	* Sistema de niveles progresivos.

Características Principales:
 *Clases jugables
    Vampiro: Puede robar vida al atacar
    Asesino: Daños críticos más altos

 *Enemigos:
    Orco: alto daño base
    Esqueleto: posibilidad de ataque doble (20%)
    Mago Oscuro: puede recuperar vida si hace daño exacto de 5

Evento Amigable:

 *Encuentro con un anciano donde eliges:
    Ayudarlo → mejoras
    Robarlo → penalización

Cómo Jugar:

 1. Ejecuta el archivo el programa

 2. Selecciona tu personaje:
    1 = Vampiro
    2 = Asesino

 3. Avanza por los niveles:
    Nivel 1: Lucha contra un Orco
    Nivel 2: Encuentro amistoso
    Nivel 3: Enfrentamiento con el General Esqueleto
    Nivel 4: Batalla final contra el Mago Oscuro

 4. En cada combate elegirás:
    1 = Atacar
    2 = Curarte (+30 vida)

istema de Combate:

 *Los ataques se basan en:
    daño = daño_base * dado

 *El dado es generado con:
    rd.randint(1,5)

 *Habilidades especiales:
    Vampiro: roba vida igual al valor del dado.
    Asesino: daño elevado si el dado ≥ 4.
    Esqueleto: 20% probabilidad de ataque doble.
    Mago: recupera vida si el daño resulta exactamente en 5.

Estructura del Código:

 *Clases principales:
    Personaje (base para jugador)
    Enemigo (base para enemigos)
    Vampiro y Asesino (jugador)
    Orco, Esqueleto, Mago (enemigos)
    amigable (evento interactivo)

Flujo del juego:
    *Selección del jugador
    *Bucle principal
    *Avance por niveles
    *Combate o evento según nivel
    *Final del juego
