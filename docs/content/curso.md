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




Crear un proyecto React desde cero requiere configurar muchas herramientas (Babel, Webpack, etc.). Afortunadamente, existen herramientas que nos preparan un proyecto base listo para usar:

*   **Create React App (CRA):** Fue el estándar por mucho tiempo, muy fiable pero a veces lento.
*   **Vite:** ¡La opción moderna y **recomendada**! Es extremadamente rápido para iniciar el servidor de desarrollo y actualizar los cambios en tu código gracias a tecnologías como esbuild y los módulos ES nativos. Usaremos Vite.

### **2.2. Creando el Proyecto con Vite**

1.  Abre tu terminal.
2.  Navega (usando `cd`) a la carpeta donde quieras guardar tus proyectos.
3.  Ejecuta el siguiente comando (reemplaza `nombre-de-mi-app` con el nombre que quieras darle a tu proyecto):
    ```bash
    npm create vite@latest nombre-de-mi-app --template react
    ```
    *   `npm create vite@latest`: Usa npm para ejecutar la última versión del creador de proyectos Vite.
    *   `nombre-de-mi-app`: El nombre de la carpeta (y proyecto) que se creará.
    *   `--template react`: Le dice a Vite que queremos una plantilla configurada para React (con JavaScript).

4.  Vite podría hacerte preguntas (si no pusiste el nombre antes, o para elegir framework/variante – asegúrate de elegir `React` y `JavaScript`).
5.  Sigue las instrucciones que Vite te mostrará al final:
    ```bash
    cd nombre-de-mi-app   # Entra a la carpeta del proyecto
    npm install           # Instala las dependencias (React, etc.)
    npm run dev           # ¡Arranca la aplicación!
    ```

### **2.3. Explorando la Estructura del Proyecto**

Abre la carpeta de tu proyecto (`nombre-de-mi-app`) en tu editor de código (en VS Code, puedes escribir `code .` en la terminal dentro de la carpeta). Verás algo así:

*   `node_modules/`: Carpeta con todas las librerías instaladas por `npm install`. ¡No la toques!
*   `public/`: Archivos estáticos (como el favicon) que se copian directamente.
*   `src/`: **¡Aquí vivirás!** Contiene tu código fuente React (componentes, CSS, etc.).
*   `.gitignore`: Le dice a Git qué archivos ignorar (importante: `node_modules`).
*   `index.html`: El único archivo HTML. Tu aplicación React se "montará" dentro del `<div id="root">` que hay aquí.
*   `package.json`: Define tu proyecto: nombre, versión, scripts (como `dev`, `build`), y dependencias (las librerías que usa tu proyecto).
*   `package-lock.json`: Fija las versiones exactas de las dependencias instaladas.
*   `vite.config.js`: Configuración específica de Vite (puedes ignorarla por ahora).

### **2.4. Archivos Clave en `src/`**

*   `main.jsx`: **El punto de entrada de tu aplicación.** Importa React, ReactDOM, tu componente principal (`App`), y le dice a ReactDOM dónde renderizar tu aplicación en el `index.html`. La extensión `.jsx` significa que contiene código JSX.
*   `App.jsx`: **Tu primer componente React.** Es el componente raíz que se renderiza inicialmente. Aquí empezarás a construir tu interfaz.
*   `index.css`: Un archivo CSS para estilos globales básicos.
*   `assets/`: Una carpeta para guardar imágenes u otros recursos que importes en tus componentes.

### **2.5. ¡Arrancando la Aplicación!**

1.  Asegúrate de estar en la carpeta raíz de tu proyecto en la terminal.
2.  Si no lo hiciste antes, instala las dependencias:
    ```bash
    npm install
    ```
3.  Ejecuta el servidor de desarrollo:
    ```bash
    npm run dev
    ```
4.  Vite iniciará un servidor local (probablemente en `http://localhost:5173` o similar) y debería abrir tu navegador automáticamente en esa dirección. Verás la página de bienvenida de React + Vite.
5.  ¡Felicidades! Tu entorno de desarrollo React está funcionando. Mantén esta terminal abierta; detectará cambios en tu código y actualizará el navegador automáticamente (Hot Module Replacement - HMR).

---

## **3. JSX: Escribiendo UI en React**

### **3.1. Tu Primer Componente: "Hola Mundo"**

1.  Abre el archivo `src/App.jsx` en tu editor.
2.  Verás una función llamada `App` que devuelve una estructura que parece HTML. ¡Eso es JSX!
3.  Vamos a simplificarlo. Borra todo el contenido dentro del `return (...)` y reemplázalo por esto:
    ```jsx
    import './App.css' // Puedes mantener o quitar los imports no usados por ahora

    function App() {
      return (
        <div>
          <h1>¡Hola, Mundo React!</h1>
          <p>Mi primera aplicación React está funcionando.</p>
        </div>
      )
    }

    export default App
    ```
4.  Guarda el archivo. ¡Mira cómo tu navegador se actualiza solo mostrando tu nuevo mensaje!

### **3.2. ¿Qué es JSX? (JavaScript XML)**

*   JSX es una extensión de sintaxis para JavaScript que te permite escribir estructuras similares a HTML dentro de tu código JavaScript.
*   **No es HTML real**, ni tampoco una simple cadena de texto.
*   **¿Por qué usarlo?** Hace que definir la estructura de tus componentes sea muy visual e intuitivo.
*   **Transpilación:** El navegador no entiende JSX directamente. Herramientas como Babel (que Vite usa internamente) lo convierten en llamadas a funciones `React.createElement()` que el navegador sí entiende. No necesitas preocuparte por `createElement` ahora, solo saber que JSX es una forma más cómoda de escribirlo.

### **3.3. Reglas Fundamentales de JSX**

1.  **Devolver un Solo Elemento Raíz:** Un componente *siempre* debe devolver un único elemento JSX. Si necesitas devolver varios elementos juntos, envuélvelos en una etiqueta contenedora (como `<div>`) o usa un Fragmento de React (`<> ... </>`). El Fragmento es útil porque no añade un `<div>` extra innecesario al DOM final.
    ```jsx
    // Correcto:
    return (
      <>
        <h1>Título</h1>
        <p>Párrafo</p>
      </>
    )

    // INCORRECTO:
    // return (
    //   <h1>Título</h1>
    //   <p>Párrafo</p>
    // )
    ```
2.  **`className` en lugar de `class`:** Para añadir clases CSS, usa el atributo `className`. (`class` es una palabra reservada en JavaScript).
    ```jsx
    <div className="mi-clase">Contenido</div>
    ```
3.  **Atributos en `camelCase`:** La mayoría de los atributos HTML se escriben en `camelCase` en JSX. Ejemplos: `onclick` -> `onClick`, `tabindex` -> `tabIndex`, `maxlength` -> `maxLength`. Una excepción importante es `for` en las etiquetas `<label>`, que se convierte en `htmlFor`.
    ```jsx
    <label htmlFor="miInput">Etiqueta:</label>
    <input id="miInput" onClick={handleClick} />
    ```
4.  **Cerrar Todas las Etiquetas:** En JSX, *toda* etiqueta debe tener una etiqueta de cierre (`<div></div>`) o ser auto-cerrada si no tiene contenido (`<img src="..." alt="..." />`, `<input />`, `<br />`).

### **3.4. Incrustando JavaScript en JSX con `{}`**

Puedes insertar cualquier **expresión** de JavaScript válida directamente dentro de tu JSX usando llaves `{}`.

*   **Variables:**
    ```jsx
    const nombre = "Mundo";
    return <h1>Hola, {nombre}!</h1>; // Muestra: Hola, Mundo!
    ```
*   **Operaciones:**
    ```jsx
    return <p>Resultado: {5 * 10}</p>; // Muestra: Resultado: 50
    ```
*   **Llamadas a Funciones:**
    ```jsx
    const getAño = () => new Date().getFullYear();
    return <p>Año actual: {getAño()}</p>; // Muestra: Año actual: 2023 (o el año actual)
    ```
*   **Valores Booleanos, `null`, `undefined`:** Estos valores *no renderizan nada visible*, lo cual es útil para mostrar cosas condicionalmente (lo veremos más adelante). `0` (cero) sí se renderiza.

### **3.5. Diferencias Clave JSX vs. HTML (Resumen)**

*   `class` => `className`
*   `for` => `htmlFor`
*   Atributos => `camelCase` (ej. `onclick` => `onClick`)
*   Estilos en línea (`style`): Requieren un objeto JavaScript con claves camelCase.
    ```jsx
    <div style={{ color: 'red', fontSize: '16px', backgroundColor: 'lightyellow' }}>
      Texto con estilo
    </div>
    ```
*   Todas las etiquetas deben cerrarse (`<br />`, `<img />`, etc.).
*   Comentarios: `{/* Así se escribe un comentario en JSX */}`

---

## **4. ¿Cómo llega React al Navegador? El Renderizado**

Echemos un último vistazo al archivo `src/main.jsx`. Es el pegamento que une tu código React con el HTML de tu navegador:

1.  `import ReactDOM from 'react-dom/client';`: Importa la parte de React que sabe cómo hablar con el DOM del navegador.
2.  `ReactDOM.createRoot(document.getElementById('root'))`: Encuentra el `<div id="root">` en tu `index.html` y crea una "raíz" de React en ese punto. Es donde tu aplicación vivirá.
3.  `.render(<App />)` (o `<React.StrictMode><App /></React.StrictMode>`) : Le dice a React que renderice (dibuje) tu componente `App` (y todo lo que este contenga) dentro de esa raíz.
    *   `<React.StrictMode>` es un ayudante que activa verificaciones adicionales *solo en desarrollo* para ayudarte a encontrar posibles problemas en tu código. No afecta la aplicación final (build de producción).

**El Flujo Completo:** El navegador carga `index.html` -> `index.html` carga `main.jsx` -> `main.jsx` usa `ReactDOM` para tomar tu componente `<App />` y lo inserta dentro del `<div id="root">`.

---

## **5. ¡A Practicar! Primeros Pasos con Código**

Ahora es tu turno de experimentar. Intenta hacer lo siguiente en tu proyecto:

*   **Ejercicio 1: Modifica `App.jsx`**
    *   Cambia el contenido dentro del `return` de `App`. Añade un título (`<h1>`), un párrafo (`<p>`) y una lista desordenada (`<ul>`) con varios elementos (`<li>`).
    *   Crea una variable JavaScript (ej. `const titulo = "Mi Lista de Tareas";`) antes del `return` y úsala dentro de un `<h1>` usando `{titulo}`.
    *   Añade una `className` a algún elemento (ej. `<ul className="lista-bonita">`) y define algunos estilos simples para esa clase en `src/App.css` o `src/index.css`.
    *   Añade una imagen. Puedes descargar una, ponerla en `src/assets/`, importarla (`import miImagen from './assets/imagen.png';`) y usarla en una etiqueta `<img src={miImagen} alt="Descripción" />`. ¡Recuerda la barra de cierre `/` y el `alt`!

*   **Ejercicio 2: Crea un Nuevo Componente**
    *   Crea un nuevo archivo en `src/`, llámalo `Saludo.jsx`.
    *   Dentro de `Saludo.jsx`, define una función simple que devuelva un elemento JSX, por ejemplo:
        ```jsx
        function Saludo() {
          return <h2>¡Componente de Saludo!</h2>;
        }
        export default Saludo; // ¡No olvides exportarlo!
        ```
    *   Ahora, en `src/App.jsx`, importa tu nuevo componente al principio del archivo:
        ```jsx
        import Saludo from './Saludo';
        ```
    *   Usa tu componente dentro del JSX de `App` como si fuera una etiqueta HTML: `<Saludo />`.
        ```jsx
        function App() {
          return (
            <div>
              <h1>Mi Aplicación</h1>
              <Saludo /> {/* <-- Aquí usas tu componente */}
              <p>Más contenido...</p>
            </div>
          );
        }
        ```
    *   Guarda ambos archivos y verifica que veas el saludo en tu navegador.

---

