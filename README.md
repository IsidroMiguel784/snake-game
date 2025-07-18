# 🐍 Snake Game

Este proyecto es una recreación del clásico juego **Snake**, desarrollado desde cero utilizando **HTML5**, **CSS3** y **JavaScript puro** (sin frameworks).  
Está pensado como una práctica personal para afianzar conocimientos de programación frontend, lógica de juego, manipulación de canvas y despliegue web.

---

## 🎮 Demo en vivo

👉 Puedes jugar al juego directamente desde este enlace:  [https://isidromiguel784.github.io/snake-game/](https://isidromiguel784.github.io/snake-game/)

---

## 🧠 Descripción del juego

- Controlas una serpiente que se mueve en un tablero cuadrado.
- Tu objetivo es comer la **comida roja** que aparece aleatoriamente.
- Cada vez que comes, la serpiente crece y tu **puntuación aumenta**.
- El juego termina cuando:
  - Chocas con los bordes del tablero.
  - Chocas contigo mismo.

---

## 🕹️ Controles

- Puedes usar las **flechas del teclado** o las teclas `W`, `A`, `S`, `D` para mover la serpiente:
  - Arriba: `↑` o `W`
  - Abajo: `↓` o `S`
  - Izquierda: `←` o `A`
  - Derecha: `→` o `D`

---

## 🛠️ Características implementadas

- ✅ Movimiento fluido con dirección actual.
- ✅ Crecimiento al comer comida.
- ✅ Generación aleatoria de comida.
- ✅ Detección de colisiones con bordes y cuerpo.
- ✅ Reinicio automático al morir.
- ✅ Contador de puntuación visible.
- ✅ Código limpio y estructurado para ser escalable.

---

## 📁 Estructura del proyecto

El proyecto está organizado en carpetas de forma modular y sencilla:

SNAKE-GAME/

├── css/
│ └── style.css # Estilos del juego (fondo, colores, etc.)
├── js/
│ └── main.js # Toda la lógica y el bucle del juego
├── index.html # Estructura principal del juego
└── README.md # Este archivo de documentación


---

## 💻 Tecnologías utilizadas

| Tecnología | Uso |
|------------|-----|
| HTML5 | Estructura del juego |
| CSS3 | Estilización visual |
| JavaScript (ES6) | Lógica del juego y renderizado |
| Canvas API | Dibujo del tablero y objetos en el juego |

---

## 🚀 Cómo jugar localmente

Puedes clonar el proyecto en tu máquina y ejecutarlo en cualquier navegador moderno:

```bash
git clone https://github.com/IsidroMiguel784/snake-game.git
cd snake-game
# Luego abre el archivo index.html con doble clic o en tu navegador
