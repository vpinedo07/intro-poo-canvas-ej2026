# 🎨 Intro Canvas 2D con Programación Orientada a Objetos

## 📌 Descripción

Esta aplicación web demuestra cómo utilizar **HTML5 Canvas** junto con **JavaScript y Programación Orientada a Objetos (OOP)** para generar y renderizar figuras geométricas dinámicamente.

El programa implementa una clase llamada `Circle` que permite crear objetos gráficos reutilizables. La aplicación muestra tres escenarios distintos:

1. Creación de un objeto mediante OOP.
2. Generación de un objeto con posición y tamaño aleatorios.
3. Generación de múltiples objetos de forma dinámica.

El objetivo es comprender cómo los **objetos en JavaScript pueden representar elementos gráficos dentro de un Canvas**.

---

# 🧠 Conceptos aplicados

Esta aplicación permite reforzar los siguientes conceptos de desarrollo web:

- HTML5 Canvas
- JavaScript moderno
- Programación Orientada a Objetos
- Renderizado gráfico 2D
- Generación de valores aleatorios
- Uso de arrays para almacenar objetos
- Manipulación del contexto gráfico (`CanvasRenderingContext2D`)

---

# 🏗️ Estructura del proyecto

project/
│
├── index.html
│
├── assets/
│ ├── css/
│ │ └── styles.css
│ │
│ ├── js/
│ │ └── main.js
│ │
│ └── img/
│ └── favicon.png
│
└── README.md


---

# ⚙️ Funcionamiento de la aplicación

La aplicación crea **tres canvas independientes**:

| Canvas | Descripción |
|------|------|
| canvasOOP | Dibuja un círculo fijo utilizando la clase `Circle`. |
| canvasRandom | Genera un círculo en una posición aleatoria dentro del canvas. |
| canvasMultiple | Genera múltiples círculos utilizando un arreglo de objetos. |

---

# 🧩 Clase `Circle`

La clase `Circle` encapsula la lógica necesaria para representar y dibujar un círculo.

### Constructor

```javascript
constructor(x, y, radius, color, text, backcolor, textColor)