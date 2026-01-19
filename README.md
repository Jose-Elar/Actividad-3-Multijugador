# Actividad-3-Multijador-
Arnaitz,Mario,Melina,José

# Motor: Unreal Engine 5
# Tipo: Arcade competitivo 2 jugadores

Desert Driver es un videojuego arcade multijugador en red local (LAN) para dos
jugadores en el que cada participante controla un vehículo todoterreno dentro de un
entorno desértico estilizado.
El objetivo es recolectar esferas de energía distribuidas por el mapa antes que el rival y
alcanzar 50 puntos para ganar la partida.
El juego está diseñado para partidas rápidas, competitivas y dinámicas centradas en
movilidad, control del vehículo y toma de decisiones estratégicas.

# Dinámica Multijador
Modo: LAN 2 jugadores
Arquitectura: Listen Server
Flujo:
Jugador 1 crea Host desde el menú.
Jugador 2 se une introduciendo IP local.
Cada jugador controla su propio coche replicado.
Los puntos se almacenan por jugador (PlayerState replicado).
Los objetos recogidos desaparecen para ambos jugadores (autoridad del servidor).

# Justificacion Técnica
El uso de Unreal Engine 5 permite:
• Replicación sencilla de vehículos.
• Arquitectura listen server ideal para LAN.
• Gestión de PlayerState para puntuaciones individuales.
• Sincronización eficiente de actores recogibles.
• Implementación rápida en Blueprints sin servidor dedicado.
La solución cumple totalmente los requisitos de juego online en red local solicitados

