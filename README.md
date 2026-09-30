# Web Calculator with History 🧮

Calculadora web desarrollada con **HTML5**, **CSS3** y **JavaScript Vanilla** (ES5). Incluye panel de historial persistente mediante `localStorage`, soporte nativo para eventos de teclado e interfaz responsiva con temática oscura estilo entorno de desarrollo[cite: 2].

---

## 🎨 Características

- **Operaciones Básicas**: Suma, resta, multiplicación y división con manejo de decimales y prevención de división por cero (`Error`)[cite: 2].
- **Historial Persistente**: Guarda automáticamente las operaciones calculadas en el almacenamiento local del navegador (`localStorage`)[cite: 2].
- **Soporte de Teclado**: Permite operar la calculadora mediante el teclado (números, operadores, `Enter`/`=` para calcular, `Backspace` para borrar dígito y `Escape` para limpiar)[cite: 2].
- **Visualización Dual**: Muestra la expresión en curso y el valor/resultado principal de forma independiente[cite: 2].
- **Diseño Adaptativo**: Layout en dos columnas que se ajusta a una sola columna en pantallas móviles (`@media max-width: 640px`)[cite: 2].
- **Sin Librerías**: Implementado completamente en JavaScript puro sin dependencias externas[cite: 2].

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica del panel de la calculadora y del historial[cite: 2].
- **CSS3**: Layouts con CSS Grid y Flexbox, variables de color y diseño responsivo[cite: 2].
- **JavaScript (ES5)**: Manipulación del DOM, lógica de cálculo, manejo de eventos de teclado y API de `localStorage`[cite: 2].

---

## ⌨️ Atajos de Teclado

| Tecla | Acción |
| :--- | :--- |
| `0` - `9` | Inserción de dígitos[cite: 2] |
| `.` | Punto decimal[cite: 2] |
| `+`, `-`, `*`, `/` | Operadores aritméticos[cite: 2] |
| `Enter` o `=` | Calcular resultado[cite: 2] |
| `Backspace` | Borrar último dígito (⌫)[cite: 2] |
| `Escape` | Limpiar calculadora (C)[cite: 2] |

---

## 📁 Estructura del Proyecto

```text
.
└── index.html     # Interfaz, estilos y lógica integrada
