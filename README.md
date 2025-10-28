Proyecto: SortiMons - La Aventura del Ordenamiento

1. Descripción General

SortiMons es una plataforma educativa gamificada que transforma el aprendizaje de algoritmos de ordenamiento en una aventura interactiva. Los usuarios exploran un mundo al estilo "Pokémon", donde cada "Gimnasio" representa un método de ordenamiento (Burbuja, QuickSort, etc.). Al entrar, se enfrentan a un desafío de aprendizaje que combina visualización en tiempo real, un "debugger" de código sincronizado y un asistente de IA para una comprensión profunda.

2. Concepto Central: El Mundo Abierto

La experiencia de usuario principal se centra en un mapa 2D (estilo retro RPG) por el que el usuario puede caminar con un avatar.

Mapa Interactivo: El mundo está lleno de "Gimnasios de Ordenamiento".

Multijugador Visual: Los usuarios pueden ver a otros jugadores caminando por el mapa en tiempo real. Esta interacción es puramente visual y no incluye chat en el mapa ni colisiones, creando una sensación de comunidad sin complejidad de interacción.

Gimnasios Temáticos: Cada gimnasio (Burbuja, Inserción, QuickSort, MergeSort) tiene un diseño único. Al entrar, la pantalla cambia a la interfaz de aprendizaje.

3. Interfaz de Aprendizaje (Dentro del Gimnasio)

Al entrar a un gimnasio, la pantalla se divide en dos o tres secciones principales:

a. Visualizador de Algoritmos

Una representación gráfica (barras, bloques, etc.) del conjunto de datos.

Los usuarios pueden ver cómo los elementos se comparan y mueven en tiempo real.

Controles para Pausar, Reiniciar, Acelerar y Desacelerar la animación.

b. El "Debugger" Sincronizado

Una vista de código fuente del algoritmo que se está ejecutando.

Resaltado de Línea: La línea de código exacta que se está ejecutando en el visualizador se resalta, moviéndose paso a paso.

Selector de Lenguaje: Los usuarios pueden cambiar el código que ven entre diferentes lenguajes (ej. Python, JavaScript, C++, Java) y el resaltado continuará funcionando.

Puntos de Interés: El código tendrá comentarios explicando las partes clave (ej. "inicio del bucle", "condición de intercambio").

c. Asistente IA: El Jaguar Sabio

Un panel de chat donde una IA (con la personalidad de un "Jaguar Sabio") explica lo que está sucediendo.

Explicación en Tiempo Real: A medida que el algoritmo avanza, el Jaguar escribe: "¡Observa! Estamos comparando el 5 y el 2. Como 5 es mayor, los intercambiamos. Esta es la lógica de la línea 7".

Interactivo: Los usuarios pueden hacer preguntas al Jaguar ("¿Por qué QuickSort es más rápido en este caso?", "¿Qué es la complejidad O(n²)?").

4. Características Adicionales y Gamificación

Sistema de Apuestas (Dinero Falso):

Antes de correr un algoritmo, los usuarios pueden "apostar" (con una moneda virtual del juego) sobre cuántos intercambios o comparaciones tomará.

Fomenta la comprensión de la eficiencia del algoritmo según el estado inicial de los datos (casi ordenado, inverso, aleatorio).

Sistema de Cuentas y Base de Datos:

Inicio de sesión de usuario (OAuth y/o email/contraseña).

Una base de datos (Firestore/MongoDB) para guardar el progreso del usuario, las medallas de gimnasio obtenidas y su saldo de moneda virtual.

Chat en Línea:

Un chat global (separado del mapa y del Jaguar) donde los usuarios pueden discutir sobre algoritmos, pedir ayuda o socializar.

5. Versión "Pro" y Monetización (Futuro)

Versión Gratuita: Acceso a los 4 gimnasios principales y todas las funciones básicas.

Versión Pro (Suscripción):

Acceso a "Gimnasios Élite" (algoritmos más complejos: Radix Sort, HeapSort, etc.).

Acceso a "Dojos de Estructuras de Datos" (visualización de Árboles, Grafos, Listas Enlazadas).

Skins exclusivas para el avatar.

Temas personalizados para el editor de código.

Integración Web3 (Experimental/Pro):

NFTs de Medallas: Al completar un gimnasio de élite, los usuarios "Pro" pueden optar por mintear su medalla como un NFT (en una red de bajo costo) como prueba de logro.

Criptomoneda del Juego: El dinero falso podría tener un puente opcional a una criptomoneda real para comprar skins o NFTs raros (esto requiere una consideración legal y ética significativa).

6. Soporte y Bienestar

Psicólogo / Coach de Estudio: Dado que aprender a programar puede ser estresante, se podría integrar un chatbot (separado del Jaguar) enfocado en el bienestar, técnicas de estudio (como Pomodoro) y manejo de la frustración (el "psicólogo" mencionado).
