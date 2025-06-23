# Adivina-el-numero

"Adivina el Número" es un juego interactivo desarrollado con React y Vite donde el objetivo es adivinar un número secreto generado aleatoriamente entre 1 y 100. El usuario ingresa un número y recibe pistas para saber si el número a adivinar es mayor o menor, hasta lograr acertar.

El juego muestra la cantidad de intentos realizados y permite reiniciar la partida para comenzar de nuevo con un nuevo número aleatorio. Está diseñado con una arquitectura basada en componentes reutilizables y usa hooks de React para manejar el estado y eventos.

Funcionalidades
Número secreto aleatorio generado al iniciar o reiniciar el juego.

Entrada validada para números entre 1 y 100.

Mensajes dinámicos para pistas y aciertos.

Contador de intentos.

Reinicio del juego con un botón.

Interfaz sencilla, intuitiva y responsiva.

Tecnologías
React (Hooks: useState, useEffect)

Vite para desarrollo rápido y moderno

JavaScript moderno (ES6+)

Cómo usar
Clona este repositorio o descarga el código.

Ejecuta npm install para instalar dependencias.

Ejecuta npm run dev para iniciar el servidor local.

Abre la URL que muestra Vite en tu navegador.

Empieza a jugar ingresando números y adivina el número secreto.

Estructura del Proyecto
src/components/Game.jsx: Componente principal que maneja la lógica del juego.

src/components/InputNumber.jsx: Campo para ingresar el número.

src/components/Message.jsx: Muestra pistas o mensajes.

src/components/RestartButton.jsx: Botón para reiniciar el juego.

src/App.jsx: Renderiza el componente Game.
