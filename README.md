# Cuestionario Diagnóstico 📋

Un cuestionario interactivo con respuestas codificadas por colores para evaluar nivel de experiencia, disponibilidad y objetivos de aprendizaje.

## Características ✨

- **Interfaz moderna y responsiva** - Funciona en desktop y móvil
- **Sistema de colores dinámico** - Cada respuesta tiene su propio color
- **Barra de progreso** - Visualiza tu avance en el cuestionario
- **Navegación intuitiva** - Botones anterior/siguiente y reinicio
- **Cálculo automático de resultados** - Obtén tu puntuación y nivel
- **Sin dependencias externas** - HTML, CSS y JavaScript vanilla

## Cómo usar 🚀

1. **Abre el archivo** `index.html` en tu navegador
2. **Responde las preguntas** seleccionando una opción (cada una tiene un color)
3. **Navega** con los botones Anterior/Siguiente
4. **Obtén resultados** al finalizar el cuestionario

## Personalización 🎨

### Cambiar preguntas y respuestas

Edita el array `quizData` en `script.js`:

```javascript
const quizData = [
    {
        id: 1,
        question: "Tu pregunta aquí",
        answers: [
            { text: "Opción 1", color: "red", value: 1 },
            { text: "Opción 2", color: "green", value: 3 },
        ]
    },
    // Más preguntas...
];
```

### Colores disponibles

- `red` - Rojo
- `orange` - Naranja
- `yellow` - Amarillo
- `green` - Verde
- `blue` - Azul
- `purple` - Púrpura

### Ajustar el algoritmo de puntuación

Modifica la función `calculateLevel()` en `script.js` para cambiar cómo se clasifican los resultados.

## Estructura del proyecto 📁

```
cuestionario/
├── index.html      # Estructura HTML
├── styles.css      # Estilos y animaciones
├── script.js       # Lógica del cuestionario
└── README.md       # Este archivo
```

## Vista previa 👀

El cuestionario incluye:
- Preguntas sobre experiencia, tiempo disponible, objetivos y motivación
- Respuestas con colores visuales que facilitan la lectura
- Sistema de puntuación automático
- Resultados con clasificación por nivel

## Licencia 📄

Libre para usar y modificar.
