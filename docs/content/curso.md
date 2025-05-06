# **Estructura del Curso: React Básico (10 Clases x 6 horas)**

**Clase 1: Introducción a React y Configuración del Entorno (6 horas)**

*   **Bloque 1 (1.5h):**
    *   ¿Qué es React? ¿Por qué usarlo? Conceptos clave (SPAs vs MPAs, Virtual DOM).
    *   Alternativas a React (Angular, Vue) - Breve comparación.
    *   Prerrequisitos del curso (Node.js, npm/yarn/pnpm, editor de código).
    *   Instalación de Node.js y gestor de paquetes.
*   **Bloque 2 (1.5h):**
    *   Configuración del proyecto: Uso de Vite (recomendado) o Create React App.
    *   Estructura básica de un proyecto React generado.
    *   Archivos principales (`index.html`, `main.jsx`/`index.js`, `App.jsx`/`App.js`).
    *   Arrancar la aplicación de desarrollo.
*   **Bloque 3 (1.5h):**
    *   Tu primer componente: "Hello World".
    *   Entendiendo JSX: Sintaxis, reglas (un solo elemento raíz, `className`, `{}`).
    *   Incrustar expresiones JavaScript en JSX.
    *   Diferencias entre JSX y HTML.
*   **Bloque 4 (1.5h):**
    *   Renderizado de elementos en el DOM (`ReactDOM.createRoot().render()`).
    *   Ejercicios prácticos: Crear y renderizar varios componentes básicos, practicar sintaxis JSX.
    *   Sesión de preguntas y respuestas.

**Clase 2: Componentes y Propiedades (Props) (6 horas)**

*   **Bloque 1 (1.5h):**
    *   ¿Qué es un componente en React? Tipos de componentes (Funcionales vs Clases - enfoque en Funcionales).
    *   Creación de componentes funcionales.
    *   Importación y exportación de componentes.
*   **Bloque 2 (1.5h):**
    *   Composición de componentes: Anidar componentes.
    *   Propiedades (Props): Concepto y propósito.
    *   Pasar datos de un componente padre a un componente hijo a través de props.
*   **Bloque 3 (1.5h):**
    *   Destructuring de props.
    *   `props.children`: Renderizar contenido anidado.
    *   Valores por defecto para las props.
    *   Validación básica de props (usando PropTypes - opcional pero útil).
*   **Bloque 4 (1.5h):**
    *   Ejercicios prácticos: Crear una estructura de componentes (ej. Layout básico, Card con título y descripción pasados por props).
    *   Sesión de preguntas y respuestas.

**Clase 3: Estado (State) con el Hook `useState` (6 horas)**

*   **Bloque 1 (1.5h):**
    *   ¿Qué es el estado en React? ¿Por qué es necesario?
    *   El Hook `useState`: Introducción y sintaxis.
    *   Declarar una variable de estado y su función actualizadora.
*   **Bloque 2 (1.5h):**
    *   Actualizar el estado: Uso de la función actualizadora.
    *   Entendiendo la inmutabilidad del estado (objetos y arrays).
    *   Cómo actualizar correctamente objetos y arrays en el estado.
*   **Bloque 3 (1.5h):**
    *   Múltiples variables de estado en un componente.
    *   Actualizaciones de estado basadas en el estado previo (usando un callback en el setter).
*   **Bloque 4 (1.5h):**
    *   Ejercicios prácticos: Crear componentes interactivos (ej. Contador simple, Toggle button, Mostrar/Ocultar un elemento).
    *   Sesión de preguntas y respuestas.

**Clase 4: Manejo de Eventos (6 horas)**

*   **Bloque 1 (1.5h):**
    *   Manejo de eventos en React (eventos sintéticos).
    *   Diferencias con el manejo de eventos nativo de JavaScript.
    *   Eventos comunes: `onClick`, `onChange`, `onSubmit`.
*   **Bloque 2 (1.5h):**
    *   Funciones manejadoras de eventos: Cómo definirlas.
    *   Pasar argumentos a las funciones manejadoras de eventos.
    *   Acceder al objeto del evento (`event`).
*   **Bloque 3 (1.5h):**
    *   Combinar manejo de eventos con estado: Cambiar el estado en respuesta a una interacción del usuario.
    *   Prevenir el comportamiento por defecto del navegador (`event.preventDefault()`).
*   **Bloque 4 (1.5h):**
    *   Ejercicios prácticos: Crear botones que cambian el estado, elementos clickeables, interacción básica entre componentes padre/hijo a través de funciones pasadas como props.
    *   Sesión de preguntas y respuestas.

**Clase 5: Renderizado Condicional y de Listas (6 horas)**

*   **Bloque 1 (1.5h):**
    *   Renderizado condicional: Mostrar u ocultar elementos basado en condiciones.
    *   Técnicas: `if`/`else` (fuera del return), operador ternario (`condition ? true : false`), operador lógico `&&`.
*   **Bloque 2 (1.5h):**
    *   Renderizado de listas de elementos.
    *   Uso del método `map()` de arrays en JSX.
    *   Renderizar una lista de componentes.
*   **Bloque 3 (1.5h):**
    *   La prop `key`: Por qué es necesaria y cómo usarla correctamente.
    *   Reglas para elegir una buena `key`.
    *   Ejemplos de renderizado condicional dentro de listas.
*   **Bloque 4 (1.5h):**
    *   Ejercicios prácticos: Mostrar diferentes mensajes según el estado, renderizar una lista de ítems (ej. lista de tareas, lista de productos), filtrar ítems en una lista usando renderizado condicional.
    *   Sesión de preguntas y respuestas.

**Clase 6: Trabajando con Formularios Controlados (6 horas)**

*   **Bloque 1 (1.5h):**
    *   Formularios en HTML vs Formularios en React.
    *   Componentes controlados vs no controlados (enfoque en controlados).
    *   ¿Qué es un componente controlado?
*   **Bloque 2 (1.5h):**
    *   Capturar el valor de un campo de entrada (`<input>`).
    *   Manejar el estado de un solo campo de entrada.
    *   Sincronizar el valor del input con el estado.
*   **Bloque 3 (1.5h):**
    *   Manejar múltiples campos de entrada (ej. usando un objeto en el estado).
    *   Manejar otros tipos de entrada: `<textarea>`, `<select>`, `<input type="checkbox">`, `<input type="radio">`.
*   **Bloque 4 (1.5h):**
    *   Manejo del envío del formulario (`onSubmit`).
    *   Validación básica del formulario (client-side).
    *   Ejercicios prácticos: Crear un formulario de registro o contacto sencillo que capture los datos y los muestre/loguee al enviarlo.
    *   Sesión de preguntas y respuestas.

**Clase 7: Efectos Secundarios con el Hook `useEffect` (6 horas)**

*   **Bloque 1 (1.5h):**
    *   ¿Qué son los efectos secundarios? (Data fetching, suscripciones, manipulación manual del DOM, timers).
    *   El Hook `useEffect`: Propósito y sintaxis básica.
    *   Cuándo y por qué usar `useEffect`.
*   **Bloque 2 (1.5h):**
    *   El array de dependencias de `useEffect`.
    *   Efecto que se ejecuta solo al montar el componente (array vacío `[]`).
    *   Efecto que se ejecuta en cada renderizado (sin array de dependencias - generalmente no recomendado).
*   **Bloque 3 (1.5h):**
    *   Efecto que se ejecuta cuando cambian ciertas dependencias (array con variables).
    *   Función de limpieza (cleanup function): ¿Cuándo y cómo usarla? (ej. limpiar timers, cancelar suscripciones).
*   **Bloque 4 (1.5h):**
    *   Ejercicios prácticos: Usar `useEffect` para cambiar el título de la página, configurar/limpiar un timer, loguear el estado o props cuando cambian.
    *   Sesión de preguntas y respuestas.

**Clase 8: Peticiones HTTP (Data Fetching) (6 horas)**

*   **Bloque 1 (1.5h):**
    *   ¿Cómo obtener datos de una API en React?
    *   Realizar peticiones HTTP con la API nativa `fetch`.
    *   Alternativas: Librerías como Axios (breve mención).
*   **Bloque 2 (1.5h):**
    *   Integrar peticiones HTTP con `useEffect`.
    *   Manejar el estado de "carga" (loading).
    *   Manejar el estado de "error".
*   **Bloque 3 (1.5h):**
    *   Mostrar los datos obtenidos (usando renderizado de listas y condicional).
    *   Ejemplo práctico: Obtener una lista de posts, usuarios o productos de una API pública (ej. JSONPlaceholder).
*   **Bloque 4 (1.5h):**
    *   Ejercicios prácticos: Construir un componente que fetchea datos de una API y los muestra, añadir indicadores de carga y mensajes de error.
    *   Sesión de preguntas y respuestas.

**Clase 9: Construcción de un Proyecto Pequeño (Parte 1) (6 horas)**

*   **Bloque 1 (1.5h):**
    *   Introducción al proyecto: Definir un proyecto sencillo que integre la mayoría de los conceptos aprendidos (ej. una lista de tareas To-Do, una galería de imágenes con búsqueda, un listado de productos simple con filtro). Elegir uno y definir el alcance.
    *   Diseño de la estructura de componentes para el proyecto.
*   **Bloque 2 (1.5h):**
    *   Configuración inicial del proyecto.
    *   Implementar los componentes base (Layout, Input para añadir, Lista para mostrar).
    *   Establecer el estado inicial de la aplicación.
*   **Bloque 3 (1.5h):**
    *   Implementar la funcionalidad principal (ej. añadir una nueva tarea a la lista, mostrar los ítems).
    *   Manejo del estado principal de la aplicación.
    *   Paso de datos y funciones entre componentes padre e hijo.
*   **Bloque 4 (1.5h):**
    *   Ejercicios prácticos: Trabajar en la implementación del proyecto bajo supervisión.
    *   Resolución de problemas comunes.

**Clase 10: Construcción de un Proyecto Pequeño (Parte 2) y Próximos Pasos (6 horas)**

*   **Bloque 1 (1.5h):**
    *   Continuar la implementación del proyecto.
    *   Añadir funcionalidades adicionales (ej. marcar tarea como completada, eliminar tarea, aplicar filtros, buscar).
    *   Refactorización básica del código.
*   **Bloque 2 (1.5h):**
    *   Posiblemente: Persistencia básica de datos (ej. usando `localStorage` - opcional si hay tiempo).
    *   Repaso general de los conceptos clave del curso (Componentes, Props, State, Events, Conditional/List Rendering, useEffect, Data Fetching).
*   **Bloque 3 (1.5h):**
    *   Próximos pasos en el aprendizaje de React:
        *   React Router (navegación entre páginas).
        *   Context API o Redux (gestión de estado global).
        *   Más Hooks personalizados.
        *   Testing en React.
        *   Estilización avanzada (CSS Modules, Styled Components, Tailwind CSS).
        *   Despliegue de aplicaciones React.
*   **Bloque 4 (1.5h):**
    *   Sesión final de preguntas y respuestas.
    *   Presentación o revisión de los proyectos completados por los estudiantes (si aplica).
    *   Recursos adicionales para seguir aprendiendo.
    *   Cierre del curso.

---

