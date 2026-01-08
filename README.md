# 🎯 Bingo de Propósitos - Red Social

Una aplicación móvil desarrollada en **Flutter** que transforma tus metas de año nuevo en un tablero de bingo interactivo y social. Olvida las listas aburridas; visualiza tu progreso, comparte tus logros y compite sanamente con tu círculo social.

---

## ✨ Funcionalidades Principales

### 🎲 El Tablero (Core)
* **Generador de Tableros:** Crea cuadrículas personalizadas de 3x3, 4x4 o 5x5 según la dificultad de tus metas.
* **Biblioteca de Metas:** Catálogo de propósitos predefinidos por categorías (Salud, Finanzas, Aprendizaje, Viajes).
* **Celdas Interactivas:** Cada casilla funciona como un "poster" visual que cambia de estado (Pendiente, En progreso, Completado).
* **Reseñas de Metas:** Al completar un propósito, puedes escribir una breve crónica de tu experiencia y calificar la dificultad.

### 🤝 Capa Social
* **Feed de Actividad:** Un muro visual para ver cuándo tus amigos completan una casilla o cantan "¡Bingo!".
* **Perfiles de Usuario:** Historial de tableros de años anteriores, estadísticas de éxito y metas favoritas.
* **Tableros Públicos:** Explora y clona plantillas creadas por la comunidad o figuras públicas.
* **Interacción:** Sistema de "likes" y comentarios en los logros de otros usuarios.

### 📱 Integración Nativa (Widgets)
* **Widget de Pantalla de Inicio:** Visualiza tu tablero 2x2 o 3x3 directamente en Android/iOS sin abrir la app.
* **Actualización Dinámica:** El widget se sincroniza en tiempo real cada vez que marcas un avance.
* **Acceso Rápido:** Toca una casilla en el widget para ir directamente a la sección de "completar meta".

### 🏆 Gamificación
* **Sistema de Logros:** Desbloquea medallas exclusivas por rachas de días o por completar líneas específicas (Bingo horizontal, vertical o diagonal).
* **Modo Archivo:** Al finalizar el año, tu tablero se convierte en una "cápsula del tiempo" visual.
* **Shareable Assets:** Genera imágenes estéticas de tu progreso para compartir en Instagram Stories o TikTok.

---

## 🛠️ Stack Tecnológico

* **Frontend:** [Flutter](https://flutter.dev/) (Multiplataforma).
* **Backend:** [Firebase](https://firebase.google.com/) (Auth, Firestore para la base de datos social y Storage para imágenes).
* **Widgets Nativos:** [home_widget](https://pub.dev/packages/home_widget) para la comunicación entre Flutter y el sistema Android/iOS.
* **Diseño:** UI minimalista con soporte nativo para **Dark Mode**.

---

## 📐 Configuración del Widget (Android)

Para el correcto funcionamiento del widget 2x2 o 3x3, el proyecto utiliza los siguientes tamaños de celda en `appwidget-provider`:

| Tamaño | minWidth | minHeight |
| :--- | :--- | :--- |
| **2x2** | 110dp | 110dp |
| **3x3** | 180dp | 180dp |

---

## 🚀 Instalación (Desarrollo)

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/bingo-propositos.git](https://github.com/tu-usuario/bingo-propositos.git)