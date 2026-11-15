# Guía de juego y pruebas de la Alpha

## Entrar al servidor

1. Pide al equipo la dirección de conexión y, si corresponde, el puerto de tu edición.
2. En **Java**, entra en **Multijugador** y añade el servidor. En **Bedrock**, usa **Jugar → Servidores → Añadir servidor** si tu plataforma ofrece esa opción.
3. Conéctate y revisa si aparecen el mensaje de bienvenida y el marcador lateral.

## Qué probar

| Prueba | Qué observar |
| --- | --- |
| Entrada desde Java y Bedrock | Cada cliente puede conectarse al mismo mundo y ver a jugadores de la otra edición. |
| Bienvenida y marcador | Comprueba que el mensaje y el scoreboard de TAB se leen correctamente en tu edición. |
| Alcalde y misión | Interactúa con el alcalde y comprueba el inicio y progreso de **Un nuevo comienzo** (BeautyQuests, ID `1`). |
| Rangos y economía | Comprueba que se muestra tu rango cuando corresponda y que el saldo se presenta como **Milagro Coins**. |
| Protección de terrenos | En una parcela de pruebas y con permiso de su dueño, verifica qué acciones puede realizar una persona con acceso y otra sin acceso. |
| Hologramas (prueba en curso) | Si el equipo habilita un rótulo de prueba, compara en Java y Bedrock si aparece, a qué distancia se lee y si se corta el texto. |

## Reportar un fallo

Indica tu edición y versión de Minecraft, la zona o el NPC, los pasos para reproducir el fallo y qué esperabas ver. Si puedes, añade una captura que no muestre datos de conexión ni datos personales.
